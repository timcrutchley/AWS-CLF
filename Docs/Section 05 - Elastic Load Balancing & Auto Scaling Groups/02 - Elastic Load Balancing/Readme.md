# 02 - ELASTIC LOAD BALANCING
## SECTION 05 - ELASTIC LOAD BALANCING & AUTO SCALING GROUPS <br>
### < AWS: CLOUD PRACTITIONER > <br>
### 10/15/2023 <br>

<br>

### WHAT IS LOAD BALANCING? >>

Load balancers are servers that forward internet traffic to multiple servers (EC2 Instances) downstream
<br>

### WHY USE A LOAD BALANCER >>

- Spread load across multiple downstream instances
- Expose a single point of access (DNS) to your application
- Seamlessly handle failures of downstream instances
- Do regular health checks to your instances
- Provide SSL termination (HTTPS) for your websites
- High availability across zones
<br>

### WHY USE AN ELASTIC LOAD BALANCER? >>

An ELB (Elastic Load Balancer) is a **managed load balancer**
  - AWS guarantees that it will be working
  - AWS takes care of upgrades, maintenance, high availability
  - AWS  provides only a few configuration knobs

It costs less to setup your own load balancer but it will be a lot more effort on your end (maintenance, integrations)

4 kinds of load balancers offered by AWS:
  - Application Load Balancer (HTTP / HTTPS only) - Layer 7
  - Network Load Balancer (ultra-high performance, allows for TCP) - Layer 4
  - Gateway Load Balancer - Layer 3
  - Classic Load Balancer (retired in 2023) - Layer 4 & 7
<br>

### LOAD BALANCER TYPES >>

#### APPLICATION LOAD BALANCER (ALB)
**HTTP / HTTPS / gRPC protocols (Layer 7)**

HTTP Routing features

Static DNS (URL)

<br>

#### NETWORK LOAD BALANCER (NLB)
**TCP / UDP protocols (Layer 4)**

High Performance: millions of requests per second

Static IP through Elastic IP

<br>

#### GATEWAY LOAD BALANCER  (GWLB)
**GENEVE Protocol on IP Packets (Layer 3)**

Route Traffic to Firewalls that you manage on EC2 Instances

Intrusion detection
<br>
