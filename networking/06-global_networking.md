# Global Networking
## Edge networking services
## Secure and speedy networking for user-facing application data
Edge networking is the process of bringing information storage and computing abilities closer to the devices that produce that information and the users who consume it. Edge computing is important because organizations often need lower latency access to their data and content. By performing tasks or caching data locally or closer to users, organizations can deliver faster, more responsive experiences while maintaining better control over their infrastructure. There are also many different services that are hosted on the edge, like the DNS service, Amazon Route 53.

## Translating domain names to IP addresses with DNS
Suppose that AnyCompany has a website hosted in the AWS Cloud. Customers enter the web address into their browser and they are able to access the website. This happens because of DNS resolution. DNS resolution involves a customer DNS resolver communicating with a company DNS server.
You can think of DNS as being the phone book of the internet. DNS resolution is the process of translating a domain name to an IP address.
To learn more about how DNS works, choose each of the three numbered markers.

<img width="900" height="300" alt="image" src="https://github.com/user-attachments/assets/4fd0f94d-bd82-4d4b-8832-3f780dce49f5" />
<img width="900" height="300" alt="image" src="https://github.com/user-attachments/assets/89f6ce63-7617-4ab3-ac21-84d6fab835f9" />
<img width="900" height="300" alt="image" src="https://github.com/user-attachments/assets/ea4596b3-f610-425e-a37b-ff46636608ba" />
<img width="900" height="300" alt="image" src="https://github.com/user-attachments/assets/2ed6bcc2-6f75-46ea-bbe4-5dfda3e889e6" />

## Amazon Route 53

<img width="250" height="250" alt="image" src="https://github.com/user-attachments/assets/e74550d3-df5b-4d96-a1b6-e249fea32a7d" />

Route 53 is a DNS that provides a reliable and cost-effective way to route end users to internet applications.
Route 53 directs end users to your resources with globally dispersed DNS servers and automatic scaling. It gives developers and businesses a reliable way to route end users to internet applications hosted in AWS. It connects user requests to infrastructure running in AWS, such as Amazon EC2 instances and load balancers. It also routes users to infrastructure outside of AWS.
Another feature of Route 53 is the ability to manage the DNS records for domain names. You can register new domain names directly in Route 53. You can also transfer DNS records for existing domain names managed by other domain registrars. This makes it possible for you to manage all of your domain names within a single location.
Route 53 also works with the next AWS edge networking service, Amazon CloudFront.

## Amazon CloudFront

<img width="250" height="250" alt="image" src="https://github.com/user-attachments/assets/22550c91-f2ea-4c70-bcdc-256bf8a40376" />

CloudFront is a content delivery network (CDN) service that delivers your content with faster loading times, cost savings, and reliability. CloudFront is like a global network of delivery trucks that quickly brings web content to users around the world. Instead of all requests traveling back to one central warehouse (your original server), CloudFront stores copies of your content at locations closer to your users. This means websites, videos, images, and applications load much faster, no matter where your customers are located.
To learn more, expand each of the following three categories.

* Streaming video service
A company that offers online workout videos uses CloudFront to make sure videos play smoothly without buffering, even during peak exercise times when thousands of users log in simultaneously.

* Ecommerce website
An online store uses CloudFront to deliver product images and web pages quickly during busy shopping seasons. This faster experience keeps customers engaged and reduces abandoned shopping carts.

* Mobile app
A travel app uses CloudFront to deliver map data and images to users' phones quickly to help travelers navigate new cities without frustrating delays.

Now that you know a little more about CloudFront, here is an example of how it can work for customer requests. The following example describes how Route 53 and CloudFront work together to deliver content to customers. To learn more, choose each of the following numbered markers.

<img width="900" height="300" alt="image" src="https://github.com/user-attachments/assets/35bc3cc6-55ce-41b3-b3fd-ca694e6d8055" />
<img width="900" height="300" alt="image" src="https://github.com/user-attachments/assets/e59fb381-3052-45d0-a646-a8514acef1d0" />
<img width="900" height="300" alt="image" src="https://github.com/user-attachments/assets/8a42f8e1-8b36-4463-89d6-7d25f9a7d912" />
<img width="900" height="300" alt="image" src="https://github.com/user-attachments/assets/4514ec60-4133-4797-808f-d954a148e1e2" />
<img width="900" height="300" alt="image" src="https://github.com/user-attachments/assets/7b996ce2-e15a-41d2-a0e2-9d72aef577fb" />

## AWS Global Accelerator

<img width="250" height="250" alt="image" src="https://github.com/user-attachments/assets/259bbbe9-ee40-48c4-ba4b-c0a5199ac63a" />

Global Accelerator is a service that uses the AWS global network to improve application availability, performance, and security. It uses intelligent traffic routing and fast failover if something goes wrong in one of your application locations.
Global Accelerator is a networking service that helps your applications run faster and more reliably across the globe. Think of it like creating express lanes on the internet highway specifically for your application's traffic. Instead of your users' requests taking the regular, sometimes congested internet routes, Global Accelerator directs traffic through the AWS private global network—getting your users to your application faster and more reliably.

To learn more on AWS Global Accelerator, expand each of the two example use cases.

## Global gaming company
A gaming company uses Global Accelerator to reduce lag and provide smoother gameplay for players around the world. Players in Tokyo, New York, and London all experience similar, responsive gameplay because their connections are optimized.

## Financial services application
A banking app uses Global Accelerator to ensure their customers always have fast, reliable access to their accounts. Even during peak times or when network conditions in one area are poor, customers can check balances and make transactions without frustrating delays.

Several AWS edge services are similar and are used in global networking solutions. To review these AWS edge services, choose each of the following flashcards.
<img width="670" height="670" alt="image" src="https://github.com/user-attachments/assets/fa0d7b5e-9757-4223-a184-47df3111244d" />
<img width="670" height="670" alt="image" src="https://github.com/user-attachments/assets/0dbbe753-2f2b-4667-b815-9f7175b779e2" />
