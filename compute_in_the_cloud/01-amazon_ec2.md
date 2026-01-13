<img width="900" height="300" alt="image" src="https://github.com/user-attachments/assets/c6284790-36f4-4967-92e9-5270d3a1cc49" />

# Amazon EC2
<img width="280" height="265" alt="image" src="https://github.com/user-attachments/assets/20714e82-0ffb-4a4a-b151-747e9bd7bffe" />

Amazon EC2 is more flexible, cost-effective, and faster than managing on-premises servers. It offers on-demand compute capacity that can be quickly launched, scaled, and terminated, with costs based only on active usage.

The flexibility of Amazon EC2 allows for faster development and deployment of applications. You  can launch as many or as few virtual servers as needed and configure security, networking, and storage. You can also scale resources up or down based on usage, such as handling high traffic or compute-heavy tasks.
	
## **Key takeaways: Comparing on-premises and cloud resources**
When designing infrastructure for your business, selecting the right resource can significantly affect your efficiency, flexibility, and overall costs. Review the key differences between on-premises and cloud resource management.
	
## **Challenges of on-premises resources**
Imaging that you are responsible for designing your company's infrastructure to support new websites. With traditional on –premises resources, you must purchase hardware upfront, wait for delivery, and handle installation and configuration. This process is time-consuming, costly, and inflexible because you are locked into a specific capacity that might not align with changing demands.

<img width="1041" height="644" alt="image" src="https://github.com/user-attachments/assets/dfde2140-4176-4866-a812-12bb4a09739b" />
		
## **Benefits of using Cloud Resources**
In contrast, with Amazon EC2, you can quickly launch, scale, and stop instances based on your needs without the delays and upfront costs associated with traditional on-premises resources.

<img width="987" height="624" alt="image" src="https://github.com/user-attachments/assets/5df9873f-e54f-45a6-8357-d4f680323045" />

## **How Amazon EC2 Works**
You have learned that AWS manages complex infrastructure, offering on-demand compute capacity that's available whenever you need it. You can request EC2 instances and have them ready to use within minutes. But how do you actually get started?

* Accessing on-demand compute capacity
* 
<img width="615" height="445" alt="image" src="https://github.com/user-attachments/assets/d28b62be-b24d-44a1-be43-cf480a12e34c" />

With Amazon EC2, you can quickly launch connect to and use virtual instances in the cloud.

  * Lauch an instance
    
    <img width="284" height="290" alt="image" src="https://github.com/user-attachments/assets/2d619563-452e-4966-88e2-1de07a5eca76" />
	
	When launching an EC2 instance, you can start by selecting an Amazon Machine Image (AMI), which defines the operating system and 	might include additional software. You also choose an instance type, which determines the underlying hardware resources, such as 	CPU, memory and network performance.

  * Connect to the instance
    
	<img width="553" height="305" alt="image" src="https://github.com/user-attachments/assets/87582893-4403-404b-bc4a-833f2f97d18f" />

	You can connect to an EC2 instance in various ways. Applications can interact with services running on the instances over the 		network. User or administrators can connect using SSH for Linus instances or Remote Desktop Protocol (RDP) for Windows instances. 	Alternatively, AWS services like AWS  System Manager offer a secure and simplified method for accessing instances.

	<img width="824" height="360" alt="image" src="https://github.com/user-attachments/assets/a2ccc5d8-e66e-419d-9f90-c89fcdb01ff4" />

  * After you are connected to the instance, you can begin using it to run commands, install software, add storage, organize files, 	and perform other tasks.
