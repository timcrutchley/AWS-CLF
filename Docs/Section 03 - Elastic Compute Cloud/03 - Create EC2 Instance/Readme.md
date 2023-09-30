# 03 - CREATE EC2 INSTANCE

## SECTION 03 - ELASTIC COMPUTE CLOUD <br>

### < AWS: CLOUD PRACTITIONER > <br>

### 09/29/2023 <br>

<br>

### LAUNCHING AN EC2 INSTANCE RUNNING LINUX >>

- Launch first virtual server using the AWS Console
- Get a first high-level approach to the various parameters
- Observe webv server launched using EC2 user data
- Learn how to start / stop / terminate the instance
  <br>

### PEM VS PPK >>

PEM: For use with OpenSSH - Used by Mac, Linux, Windows 10

<br>

PPK: For use with Putty - Any version of windows older than Windows 10

<br>

### HTTP VS HTTPS >>

For this first example, when accessing the first example instance, make sure you are using **http** NOT **https** (infront of the IP address)
<br>

### INSTANCE PUBLIC IPS >>

If an instance is stopped and start back up, there is a chance AWS will change the public IP. For this reason, a page open to the previous instance IP will not work. The new IP must be accessed to view the instance.p

**The private IP IPv4 however, does NOT change.**
<br>

### INSTANCE INFO >>

For more information on EC2 Instances visit [**Vantage**](https://instances.vantage.sh/)
<br>
