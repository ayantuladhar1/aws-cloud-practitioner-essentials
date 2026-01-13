# Cloud in real life: Infrastructure and shared responsibility
The global ecommerce company deployed resources to multiple AWS Regions and Availability Zones.

<img width="670" height="670" alt="image" src="https://github.com/user-attachments/assets/3eb29f4f-539b-4b9b-8088-c87e91cb3196" />

* Ecommerce company expansion
  * This ecommerce company is based in Seattle, Washington in the United States. The company wants to expand to global locations. However, the further the computing infrastructure is from their customers, the longer the latency. The company decides to expand to global AWS Regions to better reach their global customers.
* Global expansion one: Ireland
  * The company deploys resources to eu-west-1 Region in Ireland. Deploying in multiple Regions increases high availability. The company increases fault-tolerance and high availability even more by deploying to two Availability Zones in this Region. 
  * The company does not need to worry about securing the data center in Ireland because securing the physical infrastructure is an AWS responsibility. The company can instead focus on securing and encrypting their data within their cloud resources.
* Global expansion two: Singapore
  * The company has a significant customer base in Asia, too. So, they deploy resources to the ap-southwest-1 AWS Region in Singapore. Rather than having to set up physical infrastructure at an international scale, which can take months or years, the company used AWS to deploy global operations within a matter of minutes.
