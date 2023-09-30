# 05 - SECURITY GROUPS & CLASSIC PORTS

## SECTION 03 - ELASTIC COMPUTE CLOUD <br>

### < AWS: CLOUD PRACTITIONER > <br>

### 09/30/2023 <br>

<br>

### !--IMPORTANT NOTE--! >>

Anytime a 'timeout' (page hangs, doesn't load) is encountered when trying to establish any kind of connection into EC2 instances.. it is 100% caused by an EC2 Security Group.

Go and check the Security Group rules to make suare there are no issues.

### INTRODUCTION TO SECURITY GROUPS >>

Security Groups are the fundamental the fundamental of network security in AWS

<br>

They control how traffic is allowed into or out of our EC2 Instances

<br>

Security groups only contain **allow** rules

<br>

Security groups rules can be referenced by IP or by security group

<br>

### SECURITY GROUPS DEEPER DIVE >>

Security groups act as a "firewall" for EC2 instances

They regulate:

- Access to Ports
- Authorized IP ranges - IPv4 and IPv6
- Control of inbound network (from other to the instance)
- Control of outbound network (from the instance to the other)

<br>

### SECURITY GROUPS DIAGRAM >>

```
_________________
  <---------------------- Security Group 1 --------------Port-22--------- Your Computer - IP XX.XX.XX
                |              Inbound                                    (authorized port 22)
                |    Filter IP / Port with Rules <-------Port-22---------       Other Computer
                |                                                         (not authorized port 22)
EC2 Instance    |
IP XX.XX.XX.XX  |
  ----------------------- Security Group 1 --------------Any-Port-------->          WWW
                |            Outbound                                        Any IP - Any Port
________________|    Filter IP / Port with Rules

```

<br>

### SECURITY GROUPS BASICS >>

Can be attached to multiple instances

<br>

Locked down to a region / VPC combination

<br>

Does live "outside" the EC2 - if traffic is blocked the EC2 instance won't see it

<br>

**It's good to maintain one seperate security group for SSH access**

<br>

If your application is not accessible (time out), then it's a security group issue

<br>

If your application gives a "connection refused" error, then it's an application error or it's not launched

<br>

All **inbound** is **blocked** by default

<br>

All **outbound** traffic is **authorized** by default

<br>

### REFERENCING OTHER SECURITY GROUPS DIAGRAM >>

```
_________________
  <---------------------------------------------Port123---------[Security Group 2]        EC2 Instance
                |                                                   (attached)             IP XX.XX.XX
                |
                |
                |       Security Group 1
EC2 Instance    |             Inbound
IP XX.XX.XX.XX  |   Auhorizing Security Group 1
  <---------------------------------------------Port123---------[Security Group 1]        EC2 Instance
                |   Auhorizing Security Group 2                     (attached)             IP XX.XX.XX
                |
                |
                |
                |                                                [Security Group 3]       EC2 Instance
________________|        Not authorized                             (attached)             IP XX.XX.XX
```

<br>

### MUST KNOW PORTS >>

**22:** SSH (Secure Shell) - log into a Linux instance
**21:** FTP (File Transfer Protocol) - upload files into a file share
**22:** SFTP (Secure File Transfer Protocol) - upload files using SSH
**80:** HTTP - access unsecured websites
**443:** HTTPS - access secured websites
**3389:** RDP (Remote Desktop Protocol) - log into a Windows instance
<br>
