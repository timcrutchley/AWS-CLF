# 04 - EC2 INSTANCE TYPE BASICS

## SECTION 03 - ELASTIC COMPUTE CLOUD <br>

### < AWS: CLOUD PRACTITIONER > <br>

### 09/30/2023 <br>

### 06/14/2024 : Reviewed <br>

<br>

### EC2 INSTANCE TYPES - OVERVIEW >>

You can use different types of EC2 instances that are optimized for different user cases

<br>

AWS has the following naming convention:

<br>

**m6.x2xlarge**

<br>

m: instance class
5: generation (AWS improved them over time)
2xlarge: size within the instance class

<br>

[Instance Types](htttps://aws.amazon.com/ec2/instance-types/)

<br>

General Purpose
Compute Optimized
Memory Optimized
Accelerated Computing
Storage Optimized
Instance Features
Measuring Instance Performance

<br>

### !- GENERAL PURPOSE -! >>

Great for a diversity of workloads such as web servers or code repositories

<br>

Balance between:

- Compute
- Memory
- Networking

<br>

For this course, **t2.micro** will be utilized, which is a General Purpose EC2 instance

<br>

**General Purpose:** [Typically tart with "T"]
General purposes instances provide a balance of compute, memory and networking resources, and can be used for a variety of diverse workloads. The instances are ideal for applications that use resources in equal proportions such as web servers and code repositories

<br>

### COMPUTE OPTIMIZED >>

Great for compute-intensive tasks that require high performance processors:

- Batch processing workloads
- Media transcoding
- High performance web servers
- High performance computing (HPC)
- Scientific modeling & machine learning
- Dedicated gaming servers

**Compute Optimized:** [Typically tart with "C"]
Compute Optimized instances are ideal for compute bound applications that benefit from high performance processors, instances belonging to this family are well suited for batch processing workloads, media transcoding, high performance web servers, high performance computing (HPC) scientific modeling, dedicated gaming servers and ad server engines, machine learning inference and other compute intense applications
<br>

### MEMORY OPTIMIZED >>

Fast performance for workloads that process large data sets in memory
Use cases:

- High performance, relational/non-relational databases
- Distributed web scale cache stores
- In-memory databases optimized for BI (business intelligence)
- Applications performing real-time processsing of big unstructured data

**Memory Optimized:** [Typically tart with "R"]
Memory optimized instances are designed to deliver fast performance for workloads that process large data sets in memory
<br>

### STORAGE OPTIMIZED >>

Great for storage-intensive tasks that require high, sequential read and write access to large data sets on local storage

Use cases

- High frequency online transaction processing (OLTP) systems
- Relational & NoSQL databases
- Cache for in-memory databases (for exmaple, Redis)
- Data warehousing applications
- Distributed file systems

**Storage Optimized:** [Typically tart with "D"]
Storage optimized instances are designed for workloads that require high, sequential read and write access to very large data sets on local storage. They are optimized to devliver thousands of low-latency, random I/O operations per seconds (IOPS) to applications
<br>

### EC2 INSTANCE TYPES: EXAMPLE >>

```
Instance      vCPU       Mem(GiB)     Storage      Network Performance        EBS Bandwidth (Mbps)
t2.micro       1            1         EBS-Only      Low to Moderate
t2.xlarge      4           16         EBS-Only          Moderate
c5d.4xlarge   16           32      1x400 NVMe SSD     Up to 10 Gbps                4,750
r5.16xlarge   64          512         EBS-Only          20 Gbps                   13,600
m5.8xlarge    32          128         EBS-Only          10 Gbps                    6,800
```

<br>

**t2.micro is part of the AWS free tier (up to 750 hours per month)**

<br>

For more information on EC2 Instances visit [**Vantage**](https://instances.vantage.sh/)

<br>
