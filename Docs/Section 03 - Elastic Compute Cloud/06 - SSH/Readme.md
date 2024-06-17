# 06 - SSH

## SECTION 03 - ELASTIC COMPUTE CLOUD <br>

### < AWS: CLOUD PRACTITIONER > <br>

### 09/30/2023 <br>

### 06/16/2024 : Reviewed <br>

<br>

### SSH SUMMARY TABLE >>

```
                      SSH      Putty    EC2 Instance
                                          Connect

Mac                    x                    x

Linux                  x                    x

Windows < 10                    x           x

Windows >= 10          x        x           x

```

<br>

### SSH TROUBLESHOOTING >>

If having issues...

1. Go over the lesson content again, may have missed something
2. Read the troubleshooting guide
3. Try EC2 Instance Connect

**If one method works (SSH, Putty, or EC2 Instance Connect) you're good**
<br>

### COMMON ISSUES >>

1. There's a connection timeout

- This is a security group issue. Any timeout (not just for SSH) is related to security groups or a firewall. Ensure your security group looks like this and correctly assigned to your EC2 instance.

<br>

2. There's still a connection timeout issue

- If your security group is properly configured as above, and you still have connection timeout issues, then that means a corporate firewall or a personal firewall is blocking the connection. EC2 Instance Connect can be used instead

<br>

3. SSH does not work on Windows

- If it says: ssh command not found, that means you have to use Putty
- If that still doesn't work, use EC2 Instance Connect

<br>

4. There's a connection refused

- This means the instance is reachable, but no SSH utility is running on the instance
- Attempt to restart the instance
- If it doesn't work, terminate the instance and create a new one. Make sure using **Amazon Linux 2**

<br>

5. Permission denied (publickey,gssapi-keyex,gssapi-with-mic)

- This means either two things:
- You are using the wrong security key or not using a security key. Please look at your EC2 instance configuration to make sure you have assigned the correct key to it.
- You are using the wrong user. Make sure you have started an Amazon Linux 2 EC2 instance, and make sure you're using the user ec2-user. This is something you specify when doing ec2-user@<public-ip> (ex: ec2-user@35.180.242.162) in your SSH command or your Putty configuration

<br>

6. Worked previously, now doesn't work

- This is probably because you have stopped your EC2 instance and then started it again today. When you do so, the public IP of your EC2 instance will change. Therefore, in your command, or Putty configuration, please make sure to edit and save the new public IP.

<br>
