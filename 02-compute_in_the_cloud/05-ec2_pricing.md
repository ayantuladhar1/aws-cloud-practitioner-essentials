# AWS Pricing Options
By understanding the different Amazon EC2 pricing options, you can make more informed decisions and optimize you costs based on your specific usage needs. Pricing Options are as follows:

## On Demand Instances

<img width="425" height="421" alt="image" src="https://github.com/user-attachments/assets/16b85db2-11bc-499f-8907-9455bb5c3626" />

Pay only for the compute capacity you consume with no upfront payments or long-term commitments required.

## Reserved Instances

<img width="417" height="424" alt="image" src="https://github.com/user-attachments/assets/7e65dec1-b30c-466a-97a5-8475ed5f22b5" />

Get a savings of up to 75 percent by committing to a 1 year or 3 year term for predictable workloads using specific instance families and AWS Regions.
	
## Spot Instances

<img width="429" height="414" alt="image" src="https://github.com/user-attachments/assets/a4a204a9-7acd-4a48-998d-28bad8c49f7e" />

Bid on spare compute capacity at up to 90 percent off the On-Demand price, with the flexibility to be interrupted when AWS reclaims the instance.
	
## Savings Plans

<img width="410" height="421" alt="image" src="https://github.com/user-attachments/assets/fc2bf614-54f8-472b-a015-d21b87a0993e" />

Save up to 72 percent across a variety of instance types and services by committing to a consistent usage level for 1 or 3 years.
	
## Dedicated Hosts

<img width="431" height="408" alt="image" src="https://github.com/user-attachments/assets/62e438ef-155b-4544-a2b2-64665890c870" />

Reserve an entire physical server for your exclusive use. This option offers full control and is ideal for workloads with strict security or licensing needs.

## Dedicated Instances

<img width="417" height="406" alt="image" src="https://github.com/user-attachments/assets/35144024-3e7c-4dd6-9184-a5ccf914339f" />

Pay for instances running on hardware dedicated solely to your account. This option provides isolation from other AWS customers.
Dedicated Hosts provides exclusive use of physical servers, offering full control over instance placement and resource allocation. This makes them ideal for security or compliance-driven workloads. But what if you don't need that level of control?
You could use Dedicated instances, which offer physical isolation from other AWS accounts while still benefiting from the flexibility and cost savings of shared infrastructure. The key difference is that Dedicated Instances provide isolation without you choosing which physical server they run on. Dedicated Hosts give you an entire physical server for exclusive use, providing complete control over instance placement and resource allocation.
Ultimately, the right choice depends on your specific workload requirements and the level of control you need over your infrastructure.

<img width="395" height="635" alt="image" src="https://github.com/user-attachments/assets/278b7898-4dc1-4c29-8491-7977b965ae1e" />

## More about Cost Optimization
To optimize costs and resource allocation, AWS offers range of pricing options including Savings Plans, Amazon EC2 Capacity Reservations, and Reserved Instances (RIs). Each of these is tailored to meet different workload and capacity needs.

* Savings Plans
  * Savings Plans offer discounts compared to On-Demand rates in exchange for a commitment to use a specified amount of compute power (measured per hour) over a one-year or three-year period. They provide flexibility pricing for Amazon EC2, AWS Fargate, AWS Lambda, and Amazon Sage Maker AI usage, regardless of instance type or AWS Region. Payment option include all upfront, Partial upfront, or No upfront.

* Capacity Reservations
  * Good for: Critical workloads with strict capacity requirements.
  * With Amazon EC2 Capacity Reservations, you reserve compute capacity in a specific Availability Zone for critical workloads. Reservations are charged at the On-Demand rate, whether used or not. You only pay for the instances you run. This is ideal for strict capacity requirements for current or future business-critical workloads.

* Reserved Instance flexibility
  * Good for: Steady-state workloads with predictable usage
  * RIs offer up to 75 percent savings over On-Demand pricing by applying discounts across instance sizes and multiple Availability Zones within a Region. When you purchase a Reserved Instance (RI) AWS automatically applies the discount to other instance sizes within the same family based on the instance size foot print. It also applies the discount across multiple Availability Zones for enhanced resource distribution and fault tolerance.
