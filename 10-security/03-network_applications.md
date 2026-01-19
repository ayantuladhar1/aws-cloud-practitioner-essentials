# Protecting Networks and Applications

## Network and application attacks
Network and application protection is another vital component of a secure environment on AWS. In the previous video, you learned about denial of service attacks that might be used against your enterprise.
Let's review how these denial of service attacks work.

<img width="670" height="670" alt="image" src="https://github.com/user-attachments/assets/73ef48b3-cfd7-40d4-9dee-59ecc7e4f130" />
<img width="670" height="670" alt="image" src="https://github.com/user-attachments/assets/e06df04e-1f9e-45f2-aa0a-4665c698f612" />
<img width="670" height="670" alt="image" src="https://github.com/user-attachments/assets/78e8cb12-3de4-4447-beea-87e67b0f14c2" />

## AWS protection through infrastructure
To learn more about how AWS infrastructure protects your network and applications, choose each of the following flashcards.

<img width="670" height="670" alt="image" src="https://github.com/user-attachments/assets/fd4e8ea1-86eb-4e11-8f3f-4dc303d5fa54" />
<img width="670" height="670" alt="image" src="https://github.com/user-attachments/assets/9d5dceb1-a58f-48d4-aa1a-2efbc2a0cad2" />

## AWS protection through services
AWS also offers the following services to help protect your network and applications.

## AWS Shield
AWS Shield Standard is designed to automatically protect AWS customers from the most common, frequently occurring types of DDoS attacks at no cost. It uses a variety of analysis techniques to detect and mitigate incoming malicious network traffic in real time.
AWS Shield Advanced is a paid service that provides detailed attack diagnostics and the ability to detect and mitigate sophisticated DDoS attacks. It also integrates with other services, such as Amazon CloudFront, Amazon Route 53, and ELB.
Additionally, you can integrate AWS Shield with AWS WAF by writing custom rules to mitigate complex DDoS attacks.

## AWS WAF
AWS WAF is a web application firewall that monitors network requests that come into your web applications. When a request comes into AWS WAF, it checks the IP address against a web access control list (web ACL). If the request comes from a blocked IP address on the web ACL, AWS WAF denies access. Legitimate requests are allowed access.
