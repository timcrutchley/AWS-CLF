# 01 - HIGH AVAILABILITY, SCALABILITY, ELASTICITY

## SECTION 05 - ELASTIC LOAD BALANCING & AUTO SCALING GROUPS <br>

### < AWS: CLOUD PRACTITIONER > <br>

### 10/12/2023 <br>

<br>

### SCALABILITY & HIGH AVAILABILITY >>

Scalability means that an application / system can handle greater loads by adpating

There are two kinds of scalability:
  - Verticle Scalability
  - Horizontal Scalability (= elasticity)

Scalability is linked but different to High Availability

<br>

### VERTICAL SCALABILITY >>

Vertical Scalability means increasing the size of the instance

For example, your application runs on a t2.micro

Scaling that application vertically means running it on a t2.large

Vertical scalability is very common for non distributed systems, such as a database

<br>

### HORIZONTAL SCALABILITY >>

Horizontal Scalability means increasing the number of instances / systems for your application

Horizontal scaling implies distributed systems

This is very common for web applications / modern applications

It's easy to horizontally scale thanks to cloud offerings such as Amazon EC2
<br>

### HIGH AVAILABILITY >>

High Availability usually goes hadn in hand with horizontal scaling

High availability means running your application / system in at least 2 Availability Zones

The goal of high availability is to survive a data center loss (disaster)
<br>

### HIGH AVAILABILITY & SCALABILITY FOR EC2 >>

Vertical Scaling: Increase instance size (= scale up / down)
  - From: t2.nano - 0.5G of RAM, I vCPU
  - To:u-12tb1.metal - 12.3TB of RAM, 448 vCPUs

Horizontal Scaling: Increase number of instances (= scale out / in)


<br>

### SCALABILITY VS ELASTICITY (VS AGILITY) >>

**SCALABILITY:** Ability to accomodate a larger load by making the hardware stronger (scale up), or by adding nodes (scale out)

**ELASTICITY:** Once a system is scalable, elasticity means that there will be some "auto-scaling" so that the system can scale based on the loead. This is "cloud-friendly": pay-per-use, match demand, optimize costs

**AGILITY: (not related scalability - distractor)** new IT resources are only a click away, which means that you reduce the time it takes to make those resources available to your developers from weeks to just minutes.
<br>
