# Solving deployment challenges
Containers provide a reliable ways to package your application's code and dependencies into a single, portable unit, making them ideal for workflows that require high security, reliability and scalability.

## Containers and VMs
A Container packages your application with everything it needs to run, so it works the same on any computer. This helps to move, update and manage. Containers are faster and lighter than virtual machines (VMs) because they share the host computer's operating system. VMs use a hypervisor to run full separate operating systems which makes them less resource-efficient and have longer startup times.

<img width="874" height="361" alt="image" src="https://github.com/user-attachments/assets/778d9ab2-103a-459d-851b-505c6c2e7981" />
	
## Deployment consistency with containers
When a developer's environment differs from staging or production, deployments can fail and become difficult to debug. Containers solve this by keeping the application's environment consistent everywhere, making deployments smoother and assisting troubleshooting.

<img width="890" height="250" alt="image" src="https://github.com/user-attachments/assets/aecf8467-1ea7-4944-ae9a-c35f2ba96e59" />

## Scaling containers with orchestration
As containerized applications scale, managing them becomes more complex. A setup that began with a few containers on a single host can quickly grow into hundreds or thousands of containers across multiple hosts. At that scale, manually handling container lifecycle, monitoring, and general operations becomes unsustainable. This is where orchestration tools come in. They automate deployment, scaling and management to keep everything running smoothly.

<img width="867" height="419" alt="image" src="https://github.com/user-attachments/assets/e436aa39-99cc-40e2-b28a-79d509deb81a" />

## AWS Container Services
AWS has set of tools for managing containers that fits into three categories
* Orchestration
* Registry
* Compute
	
## Amazon ECS

<img width="199" height="225" alt="image" src="https://github.com/user-attachments/assets/cf1900ee-972b-4b18-80d2-59704f0158c5" />

Amazon Elastic Container Service (Amazon ECS) is a scalable container orchestration service for running and managing containers on AWS, like Docker containers. Docker is a software platform for building, testing, and deploying applications quickly.
	
## Amazon ECS launch types
* Amazon ECS with Amazon EC2 is ideal for small-to-medium businesses that need full control over infrastructure. Suitable for custom applications requiring specific hardware or networking configurations with the flexibility of Amazon EC2 and the simplicity of Amazon ECS.
* Amazon ECS with AWS Fargate is perfect for startups or small teams building web applications with variable traffic. It's a serverless option-no server management required-so team can focus on development while Amazon ECS handles scaling and orchestration.
	
## Amazon EKS

<img width="199" height="225" alt="image" src="https://github.com/user-attachments/assets/a7449946-847d-4206-94eb-27a47f652486" />

Amazon Elastic Kubernetes Service (Amazon EKS) is a fully managed service for running Kubernetes on AWS. It simplifies deploying, managing and scaling containerized applications using open-source Kubernetes with ongoing support and updates from the broader community.
* Amazon EKS with Amazon EC2 is best for enterprises needing full control over infrastructure. It offers deep customization of EC2 instances alongside Kubernetes scalability-ideal for complex, large-scale workloads.
* Amazon EKS with AWS Fargate is great for teams wanting Kubernetes flexibility without managing servers. It combines Kubernetes power with serverless simplicity, helping to scale applications quickly across various use cases.
	
## Amazon ECR

<img width="199" height="225" alt="image" src="https://github.com/user-attachments/assets/bc8cbcb1-2e2f-4672-995e-8a0722847b76" />

Amazon Elastic Container Registry (Amazon ECR) is where you can store, manage and deploy container images. It supports container images that follow the Open Container Initiative (OCI) standards. You can push, pull and manage images in your Amazon ECR repositories using standard container tooling and command line interfaces (CLIs)
		
## Fargate

<img width="199" height="225" alt="image" src="https://github.com/user-attachments/assets/11b2211d-b881-4fe1-bad7-d143999f7df6" />

AWS Fargate is a serverless compute engine for containers. It works with both Amazon ECS and Amazon EKS. Fargate is a container hosting platform, unlike Amazon ECS and Amazon EKS which are both container orchestration services.
When using Fargate, you do not need to provision or manage servers. Fargate manages your server infrastructure for you. You can focus more on innovating and developing your applications and pay only for the resources that are required to run your containers.
