# 05 - ELB & ASG QUIZ

## SECTION 05 - ELASTIC LOAD BALANCING & AUTO SCALING GROUPS <br>

### < AWS: CLOUD PRACTITIONER > <br>

### 09/22/2023 <br>
### 07/29/2024 : Reviewed <br>

<br>

### QUESTION 1 >>

<details>
    <summary>
    What is the purpose of high availability in the cloud?<br>
      - Increased Scalability<br>
      - Application thriving even in case of disaster<br>
      - Access on computers and smart phones<br>
      - Handle greater loads by launching EC2 instances based on demand<br>
    </summary>
<br>
Answer:<br>
  Application thriving even in case of disaster.
</details>

<br>

### QUESTION 2 >>

<details>
    <summary>
    Which AWS offered load balancer should you use to handle hundreds of thousands of connections with low latency?<br>
      - Application Load Balancer<br>
      - Network Load Balancer?<br>
      - Elastic Load Balancer<br>
    </summary>
<br>
Answer:<br>
  A network load balancer can handle millions of requests per second with low latency. It operates at Layer 4, and is best suited for load-balancing TCP, UDP and TLS traffic with ultra high performance.
</details>

<br>

### QUESTION 3 >>

<details>
    <summary>
    Changing an EC2 Instance Type from a t3a.medium to a t3a.2xlarge is an example of what?<br>
      - Horizontal scaling<br>
      - High Availability<br>
      - Agility<br>
      - Vertical scaling<br>
    </summary>
  <br>
  Answer:<br>
Vertical scaling means increasing the size of the instance. Changing from a t3a.medium to a t3a.2xlarge is an example of a size increase.
</details>

<br>


### QUESTION 4 >>

<details>
    <summary>
    What can you use to handle quickly and automatically the changing load on your websites and applications by adding compute resources?
<br>
      - An Elastic Load Balance <br>
      - A bigger instance Type <br>
      - An Auto Scaling Group <br>
      - Health Checks on your EC2 Instances <br>
    </summary>
<br>
Answer:<br>
An Auto Scaling Group (ASG) can automatically and quickly scale-in and scale-out to match the changing load on your applications and websites.
  
</details>

<br>

### QUESTION 5 >>

<details>
    <summary>
    Which of the following statements in INCORRECT regarding Auto Scaling Groups?
<br>
      - Replace unhealthy instances<br>
      - Are cost-effective by running at optimal capacity<br>
      - Automatically register new instances to a load balancer<br>
      - Automatically changing the EC2 Instance types<br>
    </summary>
<br>
Answer:<br>

</details>

<br>


### QUESTION 6 >>

<details>
    <summary>
    What load balancer is best suited for HTTP/HTTPS load balancing traffic?<br>
      - Network Load Balancer<br>
      - Classic Load Balancer<br>
      - Elastic Load Balancer<br>
      - Application Load Balancer<br>
    </summary>
  <br>
Answer:<br>
Application Load Balancers are used for HTTP and HTTPS load balancing. They are the best suited for this kind of traffic.<br>
</details>

<br>


### QUESTION 7 >>

<details>
    <summary>
    Which of the following is NOT an Auto Scaling Strategy?<br>
      - Manual Scaling<br>
      - Dynamic Scaling<br>
      - Active Scaling<br>
      - Predictive Scaling<br>
    </summary>
  <br>
  Answer:<br>
  Active Scaling is not a Scaling Strategy. Auto Scaling Strategies include: Manual Scaling, Dynamic Scaling (Simple/Step Scaling, Target Tracking Scaling, Scheduled Scaling), and Predictive Scaling.

</details>

<br>


<br>


### QUESTION 8 >>

<details>
    <summary>
    Which AWS service offers easy horizontal scaling of compute capacity<br>
      - EBS<br>
      - AMI<br>
      - IAM<br>
      - ASG<br>
    </summary>
    <br>
  Answer:<br>
Auto-Scaling Groups (ASG) offers the capacity to scale-out and scale-in by adding or removing services based on demand.
</details>

<br>


<br>


### QUESTION 9 >>

<details>
    <summary>
    Which of the following statements is NOT a feature of Load Balancers?<br>
      - Do regular health checks on your instances<br>
      - Spread load across multiple downstream instances<br>
      - Handle failures downstream of instances<br>
      - Back-end AutoScaling<br>
    </summary>
<br>
  Answer:<br>
Load Balancers cannot help with back-end autoscaling. You should use Auto Scaling Groups.
</details>

<br>


<br>


### QUESTION 10 >>

<details>
    <summary>
    Question?
      - answer 1
    </summary>
  Answer
</details>

<br>


<br>
