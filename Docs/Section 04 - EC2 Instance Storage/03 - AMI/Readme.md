# 03 - AMI

## SECTION 04 - EC2 INSTANCE STORAGE<br>

### < AWS: CLOUD PRACTITIONER > <br>

### 10/07/2023 <br>

<br>

### AMI OVERVIEW >>

AMI = Amazon Machine Image

AMI are customization of EC2 instance

- You add your own software, configuration, operating system, monitoring
- Faster boot / configuration time because all your software is pre-packaged

AMI are built for a specific region (and can be copied across regions)

You can launch EC2 instances from"

- A Public AMI: AWS provided
- Your own AMI: you make and maintain them yourself
- An AWS Marketplace AMI: an AMI someone else made (and potentially sells)
  <br>

### AMI PROCESS (FROM AN EC2 INSTNACE) >>

Start an EC2 instance and customize it

Stop the instance (for data integrity)

Build an AMI - this will also create EBS snapshots

Launch instances from other AMIs

<br>

### AMI CREATION DETAILS >>

In order to create an AMI:

1. 'Launch Instance'
2. Copy User Data over (be sure not to create index file)
3. The instance may take a while (2-3 minutes) to be fully operational AND run the script. Even if it says running, may take longer.
4. In Instances right click on the new instance, Images > Create Image
5. Give it a name, click create
6. On the left toolbar, click "AMIs" to view

<br>

### >>

<br>

### >>

<br>

### >>

<br>

### >>

<br>

### >>

<br>
