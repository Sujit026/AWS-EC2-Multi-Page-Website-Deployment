# AWS-EC2-Multi-Page-Website
Deploying a multi-page website on AWS EC2 using Apache Web Server with custom VPC setup

**Project Overview** - 
This project demonstrates deployment of a multi-page static website on AWS EC2 using Apache Web Server. The website includes navigation between multiple pages using buttons.

**Implementation Steps**

**Step 1 - Network Setup**  
- Created a custom VPC  
- Created a Public Subnet  
- Configured Route Table and associated it with subnet  
- Attached Internet Gateway (IGW)

<img width="940" height="403" alt="image" src="https://github.com/user-attachments/assets/c2c26078-d34e-4152-8e2f-74be134cba7d" />


**Step 2 - EC2 Setup**  
- Launched EC2 instance using Amazon Linux AMI  

<img width="940" height="431" alt="image" src="https://github.com/user-attachments/assets/4760834f-9cfa-4dbb-943e-fb49c77e06a3" />


**Step 3 - Secure Access**  
- Created Key Pair (.pem)  
- Converted to .ppk using PuTTYgen  
- Connected via SSH using PuTTY  


**Step 4 - Web Server Setup**  
- Installed Apache (httpd)  
- Started and enabled Apache service  

<img width="940" height="337" alt="image" src="https://github.com/user-attachments/assets/07a1cb01-7965-4104-8aeb-cc8333d27afd" />


**Step 5 - Website Deployment**  
- Created multiple HTML pages:
  - index.html (Home)
  - about.html
  - contact.html  
- Added navigation using buttons  



**Step 6 - Hosting Website**  
- Deployed files in `/var/www/html`  
- Accessed website via EC2 Public IP 


**Output -**   

**Home page -**    

<img width="940" height="135" alt="image" src="https://github.com/user-attachments/assets/6ca7cf0b-60bb-4003-9a78-2f82f880c28d" />    

**About Me -**  

<img width="940" height="300" alt="image" src="https://github.com/user-attachments/assets/34649a8d-5bd6-4a62-a4da-8fd6a5115f14" />    

**Contact Me -**    

<img width="940" height="353" alt="image" src="https://github.com/user-attachments/assets/390a216f-9d29-4667-9fff-a51a37bb35da" />  
 




