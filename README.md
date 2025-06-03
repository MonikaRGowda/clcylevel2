# Monika R-Level 2 Report 
## TASK 1: Working of a Version Control
Version Control helps us have a track of all the changes we make and also to keep them saved in the memory. This proves itself as an advantage over normal file management. It helped me understand how we can use GitHub for tracking and making use of Git commands, such as git branch, git merge, git revert and git cherry-pick that could help us perform actions such as commit, branch, merge and etc.
This helped me gain insight of how to use Git Bash for making changes to a repository and how to hold track of all the changes the repository has gone through over the time.

![image](https://raw.githubusercontent.com/MonikaRGowda/clcylevel2/refs/heads/main/WhatsApp%20Image%202025-03-28%20at%2020.18.38%20(1).jpeg)
![image](https://raw.githubusercontent.com/MonikaRGowda/clcylevel2/refs/heads/main/WhatsApp%20Image%202025-03-28%20at%2020.18.38.jpeg)
![image](https://raw.githubusercontent.com/MonikaRGowda/clcylevel2/refs/heads/main/WhatsApp%20Image%202025-03-28%20at%2020.18.37%20(1).jpeg)


## TASK 2: Database task - DynamoDB
DynamoDB is a NoSQL database that helps in managing database not structured. So this helps in managing more data efficiently. Where as, MySQL is a SQL database that helps in managing database that is structured and present in the form of tables.
Through this task, I could understand how DynamoDB table can be used to store and manage data of various types. How the data is be exploited for different purpose. Here, I created simple user login that used access key to fetch database from DynamoDB and check the password for login.

![image](https://raw.githubusercontent.com/MonikaRGowda/clcylevel2/refs/heads/main/WhatsApp%20Image%202025-05-01%20at%2023.11.51.jpeg)


## TASK 3: Create an application on EC2 instance
EC2 is Elastic Compute Cloud, through AWS services we can create instances which  could be used as virtual computers that helps in managing applications. They can be created different zones and regions that can be accessed through SSH.
Created two instances t3.micro in different availability zones.

![image](https://raw.githubusercontent.com/MonikaRGowda/clcylevel2/refs/heads/main/WhatsApp%20Image%202025-05-07%20at%2017.42.25.jpeg)
![image](https://raw.githubusercontent.com/MonikaRGowda/clcylevel2/refs/heads/main/WhatsApp%20Image%202025-05-07%20at%2017.41.59.jpeg)
![image](https://raw.githubusercontent.com/MonikaRGowda/clcylevel2/refs/heads/main/WhatsApp%20Image%202025-05-07%20at%2017.42.10.jpeg)


## TASK 4: AWS CloudFront - Serve content from multiple S3 buckets
AWS CloudFront is a Content Delivery Network(CDN).It helps in serving content that are in S3 buckets as objects.
In this task, I created S3 bucket in which jfif files were stored. Thus, through the CloudFront Distribution, I was able to access the files through a web domain.

![image](https://raw.githubusercontent.com/MonikaRGowda/clcylevel2/refs/heads/main/WhatsApp%20Image%202025-05-04%20at%2017.19.35.jpeg)
![image](https://raw.githubusercontent.com/MonikaRGowda/clcylevel2/refs/heads/main/WhatsApp%20Image%202025-05-04%20at%2017.19.35%20(1).jpeg)
![image](https://raw.githubusercontent.com/MonikaRGowda/clcylevel2/refs/heads/main/WhatsApp%20Image%202025-05-04%20at%2017.19.34.jpeg)


## TASK 5: Kali Linux
Kali Linux is a powerful distribution that helps in penetration testing, ethical hacking, and cybersecurity research. Using Kali, penetrating open ports of virtual machine was done.We were able to search for all available ports and could penetrate through it and open a session in it. 
Understood what Kali Linux is used for and performed a simple penetration test using Nmap.Learned how to identify and analyze open ports and services.

![image](https://raw.githubusercontent.com/MonikaRGowda/clcylevel2/refs/heads/main/WhatsApp%20Image%202025-06-03%20at%2018.03.51.jpeg)
![image](https://raw.githubusercontent.com/MonikaRGowda/clcylevel2/refs/heads/main/WhatsApp%20Image%202025-06-03%20at%2018.04.04.jpeg)

## TASK 6: Socket.IO
Socket.IO is a library that allows bi-directional communication in real time. It becomes a way to connect between several clients and server.
Through this task, I could set up a basic chat application using Node.js and Socket.IO, helping multiple users to connect and share information.

![image](https://raw.githubusercontent.com/MonikaRGowda/clcylevel2/refs/heads/main/WhatsApp%20Image%202025-05-07%20at%2019.40.48.jpeg)
![image](https://raw.githubusercontent.com/MonikaRGowda/clcylevel2/refs/heads/main/WhatsApp%20Image%202025-05-07%20at%2019.40.49.jpeg)


## TASK 7: OSI
OSI (Open Systems Interconnection) is a model that tells about how computers communicate over a network.
#### Physical Layer
Transmits raw bits by provides physical servers, fiber optics, and network cables that power virtual networks and deals with cables, electrical signals, and connectors.
#### Data Link Layer
Handles MAC addressing, error detection, frame synchronization and switching between cloud network nodes .
#### Network Layer
Manages IP addressing, logical addressing and routing by determining the best physical path for data.
#### Transport Layer
Ensures reliable (TCP) or fast (UDP) communication ensuring complete data transfer by providing error checking, flow control, and retransmission.
#### Session Layer
Maintains and manages secure and persistent sessions or connecting to a cloud database or connecting between applications.
#### Presentation Layer
Encrypts, formats data by data translation and compression and translates data between the application and network format.
#### Application Layer
Acting as interface between user and network to interact with cloud apps and services providing network services to applications.

**Switching**: Process of receiving a data packet on one network port and forwarding it to another port based on its destination address.  
**Routing**: Process of selecting a path for traffic in a network, from the source device to the destination.  
**Handshakes**:  Process where two devices or systems initiate a connection and agree on how to communicate before actual data is transmitted.  
**IP Addressing**: System used to identify devices on a network which acts like its address so data knows where to go and where it came from.

![image](https://raw.githubusercontent.com/MonikaRGowda/clcylevel2/6aeaa565cfedfa347a32663d4bb123b4455b0e6e/osimodel.drawio.svg)

## TASK 8: IaaS, PaaS and SaaS
IaaS, PaaS, and SaaS are the three cloud computing service models. They help in providing ways to manage resources based on the requirements.
### IaaS (Infrastructure as a Service)
  - It provides virtualized computing resources for accessing networking features
  - It provides highest level of flexibility and management control over resources
  - The user is responsible for deploying, maintaining, and supporting  applications
  - Whereas IaaS provider is responsible for maintaining the physical infrastructure
### PaaS (Platform as a Service)
  - It provides platform with built-in software components and tools
  - It allows to focus on the deployment and management of applications making it more efficient
  - The user is responsible for developing and managing applications and data
  - Whereas PaaS provider is responsible for maintaining the physical infrastructure, operating system, middleware, and runtime environment
### SaaS (Software as a Service)
  - It provides software applications that are ready to use and run
  - It provides access to powerful software which are complete managed by the SaaS vendors
  - The user is responsible for using the application
  - Whereas SaaS provider is responsible for managing infrastructure, platform, 
 application, data storage, and updates
 

## TASK 9: Encryption Techniques - Secure Messaging App
- Caesar Cipher: In this method, letters are shifted by a fixed number of places
- Vigenère Cipher: In this, a keyword is used to shift letters and thus more secure than Caesar
- Substitution Cipher: In this, each letter is replaced with another fixed letter mapping
- SHA256:Unlike other encryption techniques that can be decrypted, this is a one way process used for passwords, making it irreversible
Created a simple GUI where messages are encrypted and decrypted on both client and server side using AES and also hashed password using SHA256.

![image](https://raw.githubusercontent.com/MonikaRGowda/clcylevel2/refs/heads/main/WhatsApp%20Image%202025-05-01%20at%2015.19.58%20(1).jpeg)
![image](https://raw.githubusercontent.com/MonikaRGowda/clcylevel2/refs/heads/main/WhatsApp%20Image%202025-05-01%20at%2015.19.59.jpeg)

## TASK 10: IP Addressing and Web Scraping - Job Listings Scraper
Web Scraping is a technique that helps in process of extracting data or content from websites using various libraries of python. Through this task I was able to understand about how to scrape a website for information and save it. It was useful in understanding dynamic web scraping.
Using various libraries of python such as Selenium, chromedriver and other libraries, it was possible to scrape a webpage that provides information of job list that includes title of the position, job description, location of company and the website link to the same. These were saved to a csv file.

![image](https://raw.githubusercontent.com/MonikaRGowda/clcylevel2/refs/heads/main/WhatsApp%20Image%202025-03-28%20at%2020.18.36%20(1).jpeg)
![image](https://raw.githubusercontent.com/MonikaRGowda/clcylevel2/refs/heads/main/WhatsApp%20Image%202025-03-28%20at%2020.18.37.jpeg)
![image](https://raw.githubusercontent.com/MonikaRGowda/clcylevel2/refs/heads/main/WhatsApp%20Image%202025-03-28%20at%2020.18.36.jpeg)
