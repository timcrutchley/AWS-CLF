# 03 - AUTO SCALING GROUPS

## SECTION 05 - ELASTIC LOAD BALANCING & AUTO SCALING GROUPS <br>

### < AWS: CLOUD PRACTITIONER > <br>

### 10/15/2023 <br>

### 07/25/2024 : Reviewed <br>

### 07/26/2024 : Reviewed <br>

<br>

### WHAT'S AN AUTO SCALING GROUP >>

In real-life, the load on your websites and application can change

In the cloud, you can create and get rid of servers very quickly

The goal of an Auto Scaling Group (ASG) is to:
  - Scale out (add EC2 instances) to match an increased load
  - Scale in (remove EC2 instances) to match a decreased load
  - Ensure we have a minimum and a maximum number of machines running
  - Automatically register new instances to a load balancer
  - Replace unhealthy instances

Cost Savings: only run at an optimal capacity (principle of the cloud)
<br>

### AUTO SCALING GROUPS IN AWS >>

#### 3 ATTRIBUTES:
Maximum Size
Actual Size / Desired Capacity
Minimum Size

Can automatically scale out & in as needed
<br>

### AUTO SCALING GROUP IN AWS WITH BALANCER >>

Load Balancers can work in tandem with Auto Scaling Group.

The Load Balancer will continue to redirect traffic over new instances as they are created/removed
<br>
