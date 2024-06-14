# 02 - EC2 BASICS

## SECTION 03 - ELASTIC COMPUTE CLOUD <br>

### < AWS: CLOUD PRACTITIONER > <br>

### 09/29/2023 <br>

### 06/13/2024 : Reviewed <br>

<br>

### AMAZON EC2 >>

EC2 is one of the most popular of AWS' offering

<br>

**EC2** = **E**lastic **C**ompute **C**loud = **I**nfrastructure **a**s **a** **S**ervice **(IaaS)**

<br>

It mainly consists in the capability of:

- Renting virtual machines (EC2)
- Storing data on virtual drives (EBS)
- Distributing load across machines (ELB)
- Scaling the services using an auto-scaling group (ASG)

<br>

### EC2 SIZING & CONFIGURATION OPTIONS>>

Operating Sytem (OS): Linux, Windows or Mac OS

<br>

How much compute power & cores (CPU)

<br>

How much random-access memory (RAM)

<br>

How much storage space:

- Network-attached (EBS & EFS)
- Hardware (EC2 Instance Store)

<br>

Network card: speed of the card, Public IP address

<br>

Firewall rules: security group

<br>

Bootstrap script (configure at first launch):EC2 User Data

<br>

### EC2 USER DATA >>

It is possible to bootstrap our instance susing an EC2 User data script

<br>

**Bootstrapping** means launching commands when a machine starts

<br>

That script is **only run once** at the instance **first start**

<br>

EC2 user data is used to automate boot tasks such as:

- Installing updates
- Installing software
- Downloading common files from the internet
- Anything you can think of

<br>

The EC2 User Data Script runs with the root user

<br>

### EC2 INSTANCE TYPES: EXAMPLE >>

```
Instance      vCPU      Mem(GiB)      Storage     Network Performance     EBS Bandwidth (Mbps)

t2.micro        1         1          EBS-Only       Low to Moderate
t2.xlarge       4        16          EBS-Only           Moderate
c5d.4xlarge    16        32       1x400 NVMe SSD    Up to 10 Gbps               4,750
r5.16xlarge    64       512          EBS-Only          20 Gbps                 13,600
m5.8xlarge     32       128          EBS-Only          10 Gbps                  6,800
```

**t2.micro is part of the AWS free tier (up to 750 hours per month)**
<br>
