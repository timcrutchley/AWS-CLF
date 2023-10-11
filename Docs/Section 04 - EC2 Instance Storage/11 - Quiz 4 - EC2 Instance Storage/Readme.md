# 11 - QUIZ 4 - EC2 INSTANCE STORAGE
## SECTION 04 - EC2 INSTANCE STORAGE<br>
### < AWS: CLOUD PRACTITIONER > <br>
### 10/10/2023 <br>


<br>

### QUESTION 1 >>

<details>
    <summary>
    Which EC2 Storage would you use to create a shared network file system for your EC2 Instances?
      - EBS Volume
      - EC2 Instance Store
      - EBS Snapshots
      - EFS
    </summary>
  Amazon EFS is a fully managed service that makes it easy to set up, scale, and cost-optimize file storage in the Amazon Cloud.
</details>

<br>

### QUESTION 2 >>

<details>
    <summary>
    Which service can be used to automate image management processes?
      - AMI
      - EC2 Image Builder
      - EBS Snapshots
      - IAM
    </summary>
  EC2 Image Builder is an automated pipepline for the creation, maintenance, validation, sharing and deployment of Linux or Windows images for use on AWS and on-premises
</details>

<br>

### QUESTION 3 >>

<details>
    <summary>
    Which of the following is a fully managed native Microsoft Windows file system?
      - EFS
      - FSx
      - EBS
    </summary>
  Amazon FSx makes it easy and cost effective to launch and run popular file systems that are fully managed by AWS. It comes in two offerings: FSx for Windows File Server (used for business applications), and FSx for Lustre (used for high-performance computing)
</details>

<br>


### QUESTION 4 >>

<details>
    <summary>
    What are AMIs NOT used for?
      - Add your own software license
      - Add your own configuration
      - Add your own operating-system
      - Add your own IP addresses
    </summary>
  You cannot use AMIs to add your IP addresses. IP addresses are added to an instance as you create it.
</details>

<br>

### QUESTION 5 >>

<details>
    <summary>
    EBS Volumes CANNOT be attached to multiple EC2 instances at a time?
      - True
      - False
    </summary>
  EBS Volumes can be attached to only one EC2 Instance at a time, but EC2 Instances can have multiple EBS Volumes attached to them.
</details>

<br>


### QUESTION 6 >>

<details>
    <summary>
    An EBS Volume is a network drive you can attach to your instances while they run, so your instances' data persist even after their termination?
      - True
      - False
    </summary>
  EBS Volumes allow instances' data to persist even after their termination
</details>

<br>


### QUESTION 7 >>

<details>
    <summary>
    Which statement is CORRECT regarding EC2 Instance Store?
      - It is not good to use as a disk to cache content
      - It has better I/O performance, but the data is lost if the EC2 Instance is terminated
      - Your data is always safe with EC2 Instance Store
    </summary>
  EC2 Instance Store has a better I/O performance, but data is lost if the EC2 Instance is stopped or terminated, or when the underlying disk drive fails.
</details>

<br>


<br>


### QUESTION 8 >>

<details>
    <summary>
    What is an EBS Snapshot?
      - The operating-system on an EC2 Instance
      - A backup of your EBS Volume at a point in time
      - The amount of CPU and RAM of an EC2 Instance
    </summary>
  EBS Snapshots are used to backup data on your EBS Volumes at a point in time
</details>

<br>


<br>


### QUESTION 9 >>

<details>
    <summary>
    Where can you find a third party's AMI so you can use it to launch your EC2 Instance?
      - Public AMIs
      - My own AMIs
      - AWS Markeplace AMIs
    </summary>
  You can use AWS Marketplace AMIs to use someone else's AMI
</details>

<br>


<br>


### QUESTION 10 >>

<details>
    <summary>
    What is an EBS Volume tied to?
      - A region
      - A data center
      - An edge location
      - An availability zone
    </summary>
  EBS Volumes are tied to only one availabilty zone
</details>

<br>


<br>
