# 01 -

## SECTION 05 - ELASTIC LOAD BALANCING & AUTO SCALING GROUPS <br>

### < AWS: CLOUD PRACTITIONER > <br>

### 08/24/2024 : Updated <br>

### 07/27/2024 : Reviewed <br>

<br>
<br>

### High Availalability vs Scalability vs Elasticity vs Agility  >>

<br>

#### High Availability:
Have applications across multiple availability zones

<br>

#### Scalability (Vertical & Horizontal):
Vertical:
Increasing the size of an instance
Horizontal:
Increasing the number of instances

<br>

#### Elasticity:
The ability to scale up & down based on demand

<br>

#### Agility
work faster by creating and deleting resources very quickly

<br>
<br>

### Elastic Load Balancers (ELB) >>

Distribute traffic across backend EC2 instances, can be Multi - Availability Zones

Support Health Checks

4 Types:
Classic(old)
Application(HTTP - Layer 7)
Network (TCP - Layer 4)
Gateway (Layer 3)

<br>

### Auto Scaling Groups (ASG) >>

Implement Elasticity for your application, spreading the load across multiple Availability Zones and Scaling accordingly
Scale EC2 instances based on the demand on your system, replace unhealthy
Integrated with ELB
<br>
