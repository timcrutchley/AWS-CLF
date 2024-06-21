# 09 - EC2 INSTANCE PURCHASING OPTIONS

## SECTION 03 - ELASTIC COMPUTE CLOUD <br>

### < AWS: CLOUD PRACTITIONER > <br>

### 09/30/2023 <br>

### 06/20/2024 : Reviewed <br>

<br>

### EC2 INSTANCES PURCHASING OPTIONS >>

**On-Demand Instances** - short workload, predictable pricing, pay by second
**Reserved** (1-3 years)

- Reserved Instances - long workloads
- Convertible Reserved Instances - long workloads with flexible instances
  **Savings Plans** (1-3 years) - commitment to an amount of usage, long workload
  **Spot Instances** - short workloads, cheap, can lose instances (less reliable)
  **Dedicated Hosts** - book an entire physical server, control instance placement
  **Dedicated Instances** - no other customers will share your hardware
  **Capacity Reservations** - reserve capacity in a specific AZ for any duration
  <br>

### EC2 RESERVED INSTANCES >>

**The percentage of discount is subject to change.**

<br>

Up to 72% discount compared to On-demand

<br>

You reserve specific instance attributes (<br>)

<br>

**Reservation Period** - 1 year (+discount) or 3 years (+++discount)

<br>

**Payment Options** - No Upfront (+), Partial Upfront (++), All Upfront (+++)

<br>

**Reserved Instance's Scope** - Regional or Zonal (reserve capacity in an Availability Zone)

<br>

Recommended for steady-state usage applications (database)

<br>

You can buy and sell in the Reserved Instance Marketplace

<br>

**Convertible Reserved Instance**

- Can change teh EC2 instance type, instance family, OS, scope and tenancy
- Up to a 66% discount

<br>

### EC2 SAVINGS PLANS >>

Get a discount based on long-term usage (up to 72% - same as RIs)

<br>

Commit to a certain types of usage ($10/hour for 1 or 3 years)

<br>

Usage beyond EC2 Savings Plans is billed at the On-Demand price

<br>

Locked to a specific instance family & AWS region (e.g., M5 in us-east-1)

<br>

Flexible across:

- Instance Size (e.g., m5.xlarge,m5.2xlarge)
- OS (e.g.)
  <br>

### !- EC2 SPOT INSANCES -! >>

Can get a discount of up to 90% compared to On-demand

<br>

Instance sthat you can "lose" at any point of time if your max price is less than the current spot price

<br>

The MOST cost-efficient instances in AWS

<br>

Useful for workloads that are resilient to failure

- Batch jobs
- Data analysis
- Image processing
- Any **distributed** workloads
- Workloads with a flexible start and end time

<br>

**!EXAM QUESTION!**:

#### EC2 Spot Instances are NOT suitable for critical jobs or databases

<br>

### EC2 DEDICATED HOSTS >>

A physical server with EC2 instance capacity fully dedicated to your use

<br>

Allows you address **compliance requirements** and **use your existing, serverbound software licenses** (per-socket, per-core, per-VM software licenses)

<br>

Purchasing Options:

- **On-demand** - pay per second for active Dedicated Host
- **Reserved** - 1 or 3 years (No Upfront, Partial Upfront, All Upfront)

<br>

The most exepnsive option

<br>

Useful for software that have complicated licensing model (BYOL - Bring Your Own License)

<br>

Or fow companies that have strong regulatory or compliance needs

<br>

### EC2 DEDICATED INSTANCES >>

Instances run on hardware that's dedicated to you

<br>

May share hardware with other instances in the same account

<br>

No control over instance placement (can move hardware after Stop/Start)

<br>

### RESORT EXAMPLE >>

The following example uses a 'Resort experience' to demonstrate how the different options would apply

<br>

**On demand:**
Coming and staying in a resort whenever you'd like, you pay the full price
<br>

**Reserved:**
Planning ahead and if you do plan to stay for a long time, you may get a good discount
<br>

**Savings Plans:**
Pay a certain amount per hour for certain period and stay in any room type (eg King, Suite, Sea View..)
<br>

**Spot instances:**
Hotel allows people to bid for the empty rooms and the highest bidder keeps the rooms. You can get kicked out at any time
<br>

**Dedicated Hosts:**
Book an entire building of the resort
<br>

**Capacity Reservations:**
Book a room for a period with full price even if you don't stay in it
<br>

### PRICE COMPARISON EXAMPLE - M4.LARGE - US-EAST-I >>

```
**Price Type                                  Price (per hour)**
On-Demand                                     $0.10
Spot Instance (Spot Price)                    $0.038 - $0.039 (up to 61% off)
Reserved Instance (1 year)                    $0.062 (No Upfront) - $0.058 (All Upfront)
Reserved Instance (3 years)                   $0.043 (No Upfront) - $0.037 (All Upfront)
EC2 Savings Plan (1 year)                     $0.062 (No Upfront) - $0.058 (All Upfront)
Reserved **Convertible** Instance (1 year)    $0.071 (No Upfront) - $0.066 (All Upfront)
Dedicated Host                                On-Demand Price
Dedicated Host Reservation                    Up to 70% off
Capacity Reservations                         On-Demand Price
```

<br>

### EXAM EXPECTATIONS

The CLF exam will expect you to know which instance should handle what kind of workload
<br>
