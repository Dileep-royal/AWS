# AWS
![AWS](https://d1.awsstatic.com/logos/aws-logo-lockups/poweredbyaws/PB_AWS_logo_RGB_REV_SQ.8c88ac215fe4e441dc42865dd6962ed4f444a90d.png)
# Learning for CLF-C01 Certification
![CLF-C01](https://d1.awsstatic.com/training-and-certification/certification-badges/AWS-Certified-Cloud-Practitioner_badge.634f8a21af2e0e956ed8905a72366146ba22b74c.png)
## Introduction about the certification
 By doing this entry-level certification,we may come to know about following things:
 * Cloud Architecture
 * Cloud Concepts
 * Cloud Deployment Models
 * Close look at AWS Core Services
 * Identity,Security & Governance of the Cloud
 * Billing,Pricing & Support of AWS Services
## About Exam
In the exam, we will have a total of 65 questions.  

From 65, we have 50 Scored and 15 Unscored(no marks alloted) questions.  

we have to score a 700 out of 1000 marks to get pass.  

### weightage
* Domain-1 :    

    **Cloud Concepts**         -  26%, 13 questions

* Domain-2 :  
  
    **Security & Complaince**  -  25%, 16-17 questions

* Domain-3 :  
 
    **Technology**             -  33%, 21-22 questions

* Domain-4 :  

    **Billing and Pricing**     - 16%, 10-11 questions 

Check the official Exam Guide[Click Here](https://d1.awsstatic.com/training-and-certification/docs-cloud-practitioner/AWS-Certified-Cloud-Practitioner_Exam-Guide.pdf)  

# Cloud Concepts
## === DAY-1 ===

### Essentials of a Business Applictaion
In order to Develop a E-commerce web Applications:
the resources required are:
1. Compute  - Servers, to process and the run the web applications.
2. Database -  To store data of your users and sales details.
3. Storage  - To store images and vedios of the products.
4. Networking - To allow users to connect to web application.
5. Security  - To prevent the data theft of your data.  

### Advantages/Benefits of Cloud**
* **Elasticity -** The Ability to adopt to workload cahnges (usually dynamic,short-term) .

  Eg: During Fifa world Cup, Streaming Applications Handling huge spike of traffic by increasing servers. 
* **Scalability -** The Ability to handle increased workloads by adding resources (usually static,long-term)  
  .
  Eg: scale up the database because the size has grown over time.
* **High Availability -** The Ability to continue functioning even if some components fail.  

  Eg: when a power outage causes one data center to go down ,traffic is routed to another data center.
* **Realiability -** The Ability to function consistently and correctly when expected/all the time.  

  Eg: The services are running 24/7 and are available i.e. 99.99% uptime EC2 instance 
* **Agility -** The Ability to rapidly develop, test and launch applications to deliver business value.  

  Eg: Launching a Business Application in days rather than a month.
* **Global reach -** The ability to get closer to your customers through a global infrastrcucture.  

  Eg: AWS provides 25 Availability Zones around the world and it may incresre in future.
* **pay-as-you-go pricing -** only pay for what you use and use only when you need it.  

  Eg: An EC2 instance is used for 2 hours; only pay for 2 hours.
* **Economies of Scale -** Because of their huge size,AWS can buy things more cheaply than an individual organization can.  

  Eg: Amazon purchases servers at a fraction of the cost that you could, and pass the savings on to you
 ### AWS ECONOMICS
 
 **CapEx & OpEx**  
 
 Capital Expenses - Intial cost spent to buy hardware(H/W) and software(S/W)  
 
 Operationsl Expenses - Cost spent to Maintainance of S/W & H/W , Electricity, A/C, IT Employees hiring & Training.  
 
 **on-premises Infrastructure:**  
 
 *on-premises Expenses = CapEx + OpEx*  
 
 **Cloud Infrastructure:**  
 
 *Cloud Expenses = <50% of OpEx*  
 
 OpEx includes only Subscription fee 
 
 **Reduce Costs in AWS**
* Right Sized Infrastructure - Right Number & Kind of machines,turn on/off occasional services.
* Automation - Schedule start and stop times for servers (in case of nights,weekends,events)
* Complaince Scope - Service level PCI(Payment Card Industry) complaince
* Managed Services - use the service without worrying about creating the servers,installation and licensing cost and so on.

### Foundational services in AWS
* Compute -Elastic Compute(EC2)
* Database - Relational Database Service(RDS) & DynamoDB(NoSQL)
* Storage - Simple Storage Service(S3)
* Networking - Virtual Private Network(VPC)
* Security - Identity & Access Management(IAM)
 
## === DAY-2 ===
### AWS Well-Architected Framework
* The AWS Well-Architected Framework describes key concepts, design principles, and architectural best practices for designing and running workloads in the cloud. By answering a few foundational questions, learn how well your architecture aligns with cloud best practices and gain guidance for making improvements.  

* The AWS Well-Architected Framework helps you understand the pros and cons of decisions you make while building systems on AWS. Using the Framework helps you learn architectural best practices for designing and operating secure, reliable, efficient, cost-effective, and sustainable workloads in the AWS Cloud. It provides a way for you to consistently measure your architectures against best practices and identify areas for improvement. The process for reviewing an architecture is a constructive conversation about architectural decisions, and is not an audit mechanism. We believe that having well-architected systems greatly increases the likelihood of business success.  

* The AWS Well-Architected Framework documents a set of foundational questions that allow you to understand if a specific architecture aligns well with cloud best practices. The framework provides a consistent approach to evaluating systems against the qualities you expect from modern cloud-based systems, and the remediation that would be required to achieve those qualities.

### General Design principles
* Stop guessing your capacity needs
* Test systems at production scale
* Automate to make architectural experimentation easier
* Allow for evolutionary architectures
* Drive architectures using data
* Improve through game days

### The pillars of the framework
#### Operational Excellence
 The ability to support development and run workloads effectively, gain insight into their operations, and to continuously improve supporting processes and procedures to deliver business value.   

**Design principles:**
* Perform operations as code
* Make frequent, small, reversible changes
* Refine operations procedures frequently
* Anticipate failure
* Learn from all operational failures

#### Security 
The security pillar describes how to take advantage of cloud technologies to protect data, systems, and assets in a way that can improve your security posture.   

**Design principles:**
* Implement a strong identity foundation
* Enable traceability
* Apply security at all layers
* Automate security best practices
* Protect data in transit and at rest
* Keep people away from data
* Prepare for security events

#### Reliability
The reliability pillar encompasses the ability of a workload to perform its intended function correctly and consistently when it’s expected to. This includes the ability to operate and test the workload through its total lifecycle. This paper provides in-depth, best practice guidance for implementing reliable workloads on AWS.  

**Design principles:** 
* 
* 
* 
* 
* 

#### Performance Efficency-
The ability to use computing resources efficiently to meet system requirements, and to maintain that efficiency as demand changes and technologies evolve.   

**Design principles:**

#### Cost optimization
The ability to run systems to deliver business value at the lowest price point.   

**Design principles:**

#### Sustainability
The ability to continually improve sustainability impacts by reducing energy consumption and increasing efficiency across all components of a workload by maximizing the benefits from the provisioned resources and minimizing the total resources required.   

**Design principles:**

To Know more About AWS Architecture - [Click Here](https://aws.amazon.com/architecture/well-architected/?achp_expl1&wa-lens-whitepapers.sort-by=item.additionalFields.sortDate&wa-lens-whitepapers.sort-order=desc&wa-guidance-whitepapers.sort-by=item.additionalFields.sortDate&wa-guidance-whitepapers.sort-order=desc)

## === Day-3 ===

# SECURITY & COMPLIANCE
