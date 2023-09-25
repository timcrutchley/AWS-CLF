# 04 - AWS CLOUD OVERVIEW

## SECTION 01 - INTRODUCTION <br>

### < AWS: CLOUD PRACTITIONER > <br>

### 09/24/2023 <br>

<br>

### AWS CLOUD HISTORY >>

2002: Internally launched
2003: Amazong infrastructure is one of their core srenglths. Idea to market
2004: Launched publicly with SQS
2006: Re-launched publicly with SQS, S3 & EC2
2007: Launched in Europe
<br>

### AWS CLOUD NUMBER FACTS >>

- In 2019, AWS had $35.02 billion in annual revenue
- AWS accounts for 47% of the market in 2019 (Microsft 2nd with 22%)
- Pioner and Leader of the AWS Cloud Market for the 9th consecutive year
- Over 1,000,000 active users
  <br>

### AWS USE CASES >>

- AWS enables you to build sophisticated, scalable applications
- Applicable to a diverse set of industries
  <br>

Use cases include:

- Enterprise IT, Backup & Storage, Big Data analytics
- Website hosting, Mobile & Social Apps
- Gaming Servers
  <br>

- Some companies:
  - McDonalds
  - 21st Century Fox
  - Activision
  - Netflix
    <br>

### AWS GLOBAL INFRASTRUCTURE >>

[Infrastructure](https://infrastructure.aws/)

- AWS Regions
- AWS Availability Zones
- AWS Data Centers
- AWS Edge Locations/Points of Presence
  <br>

### AWS REGIONS >>

- AWS has Regions all aroiund the world
- Names can be us-east-1, eu-west-3...
- A region is a cluster of data centers
- Most AWS services are region-scoped
  <br>

### !-HOW TO CHOOSE AN AWS REGION-! >>

!-Potential Exam Question-!

If you need to launch a new application, where should you do it?

It depends on some factors:

- **Compliance** with data governance and legal requirements; data never leaves a region without your explicit permission
- **Proximity** to customers; reduced latency
- **Available services** within a Region: new services and new features aren't available in every Region
- **Pricing** varies region to region and is transparent in the service pricing page
  <br>

### AWS AVAILABILITY ZONES >>

- Each region has many availability zones (usually 3, min is 3, max is 6)

Example:

- ap-southeast-2a
- ap-southeast-2b
- ap-southeast-2c

- Each availability zone (AZ) is one or more discrete data centers with redundant power, networking, and connectivity

- They're seperate from each other, so that they're isolated from disasters

- They're connected with high bandwidth, ultra-low latency networking
  <br>

### AWS POINTS OF PRESENCE (EDGE LOCATIONS) >>

- Amazon has 400+ Points of Presence (400+ Edge Locatations & 10+ Regional Caches) in 90+ cities across 40+ countries
- Content is delivered to end users with lower latency

<br>

### TOUR OF THE AWS CONSOLE >>

- AWS has Global Services:

  - Identity and Access Management (IAM)
  - Route 53 (DNS service)
  - CloudFront (Content Delivery Network)
  - WAF (Web Application Firewall)

<br>

- Most AWS services are Region-scoped:
  - Amazon EC2 (Infrastructure as a Service)
  - Elastic Beanstalk (Platform as a Service)
  - Lamda (Function as a Service)
  - Rekognition (Software as a Service)

[Region Table](https://aws.amazon.com/about-aws/global-infrastructure/regional-product-services)
