# 01 - EBS OVERVIEW

## SECTION 04 - EC2 INSTANCE STORAGE<br>

### < AWS: CLOUD PRACTITIONER > <br>

### 10/01/2023 <br>

### 06/21/2024 : Reviewed <br>

<br>

### WHAT'S AN EBS VOLUME? >>

An **EBS (Elastic Block Store) Volume** is a **network** drive you can attach to your instances while they run

<br>

It allows your instances to persist data, even after their termination

<br>

They can only be mounted to one instance at a time (at the CCP level)

<br>

They are bound to a specific availability zone

<br>

Analogy: Think of them as a "network USB stick"

<br>

Free tier: 30GB of free EBS storage of type General Purpose (SSD) or Magnetic per month

<br>

NOTE: CCP - Ceritified Cloud Practioner - only one EBS can be mounted to one EC2 instance.
Associate Level (Solutions Architect, Developer, SysOps): "multi-attach" feature for some EBS

<br>

### EBS VOLUME >>

It's a network drive (i.e. not a physical drive)

- It uses the network to communicate the instance, which means there might be a bit of latency
- It can be detached from an EC2 instance and attached to another one quickly

<br>

It's locked to an Availability Zone (AZ)

- An EBS Volume in us-east-1a cannot be attached to us-east-1b
- To mvoe a volume across, you first need to snapshot it

<br>

Have a privisoned capacity (size in GBs, and IOPS)

- You get billed for all the provisioned capacity
- You can increase the capacity of the drive over time

<br>

### !-EBS - DELETE ON TERMINATION ATTRIBUTE-! >>

**!-EXAM QUESTION-!**

<br>

The Delete on Termination attribute Controls the behaviour when an EC2 instance terminates

- By default, the root EBS volume is deleted (attribute enabled)
- By default, any other attached EBS volume is not deleted (attribute disabled)

<br>

This can be controlled by the AWS console / AWS CLI

<br>

**Use case: perserve root volume when instance is terminated**

<br>
