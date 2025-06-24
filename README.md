# Descriptive Analysis
  A descriptive analysis was performed on one of the City of Vancouver (COV) datasets, titled Schools. The detailed documentation will cover the design through to implementation and evaluation.  
# Project Description
The prominent topics of this study are to analyze the data in such a way that Amazon Web Services (AWS) functionalities can be automated, which include S3, Glue DataBrew, AWS Glue, Athena, and so forth.  
# Project Title
Analysis of the school data of COV to find a solution  
# Objective
Prioritize resources and policies to establish more StrongStart BC schools than other school types.  
# Dataset
The table schema is as follows:
- ADDRESS;
- SCHOOL_CATEGORY;
- SCHOOL_NAME;
- Geom;
- Geo Local Area;
- geo_point_2d  
By observing the City of Vancouver data portal itself, a central raised question visible on the analytical graph shown in the figure below:  
![image](https://github.com/user-attachments/assets/de8f8043-74a6-4fc3-ae3d-97760b02a234)  
## Problem Analysis – Fishbone Diagram
![image](https://github.com/user-attachments/assets/8417513d-41af-444b-99f8-ca2ae0aca4b2)  
![image](https://github.com/user-attachments/assets/f84dddb8-581b-4646-bb07-04f56f8f0967)  
By using the fishbone diagram, which mainly focuses on two factors: School Distribution imbalance and Community Planning. According to our data in the school dataset, the school Distribution imbalance sounded more critical for this issue.  
# Methodology
To find out the root cause and its solution using AWS, we will go through several steps such as Ingestion, Profiling, Cleaning, Cataloging, and Summarization using Data Analytics Platform (DAP).  
# Tools and Technologies
- Amazon S3: Used to store the filtered cultural spaces dataset in its raw format.
- AWS Glue Data Catalog: Registers the dataset structure for other services like Athena.
- AWS Glue DataBrew: Used for profiling, cleaning, and validating data.
- AWS Athena: Enables querying of the dataset using SQL.
- AWS CloudWatch: Monitors and collects metrics, logs, and events for AWS resources and applications.AWS CloudTrail: Tracks user activity and API calls to audit and secure AWS accounts.
- AWS Pricing Calculator: Estimates costs for AWS services based on usage and configuration.
- Key Management Services: Manages encryption keys to secure data across AWS services.
- VPC: Creates a virtual network for isolated and customizable cloud resources.
- EC2: Provides scalable virtual servers for computing workloads in the cloud.  
# Deliverables
Since we are aware of the dataset as well as its issues with the in-premise server and fewer StrongStart BC, the deliverables of this study will be provided as follows:
- The dataset preview graph, which the COV portal has generated, helps to understand that StrongStart BC has an issue with fewer schools in each area of the City.
- Through AWS, we will find the solution to why StrongStart BC has fewer schools and what factors prevent it from having more.
- AWS will get rid of the physical servers.
- AWS will provide security through different services and features.  
# AWS Deployment and Service Models
![image](https://github.com/user-attachments/assets/57c837fa-53e3-4a8c-ae6e-013d8a7f9687)  
Case Study #1 illustrates the Private, Public, and Hybrid deployment models, each managed by specific operational teams such as the AWS and City of Vancouver (COV) Operations teams. The Private Cloud is depicted as an on-premises solution with controlled access and privacy, utilizing AWS Data Centers and a COV Account in the Virginia region. The Public Cloud is a remote solution managed by a third-party provider with developer access and configurable privacy. At the same time, the Hybrid Cloud combines elements of both, offering a configurable approach. A comparison table highlights school location, access, and privacy differences across these models.  
![image](https://github.com/user-attachments/assets/18a7308e-15ce-47e5-a2cc-a784c6085ad1)  
Case Study #2 is a variation or reiteration of Case Study #1, also covering Private, Public, and Hybrid deployment models with a similar structure. It emphasizes the operational teams and infrastructure components like servers and platforms, with the AWS Operations Team playing a central role. The models are again differentiated by location (on-premises, remote, hybrid), access (controlled, developer, configurable), and privacy (controlled, configurable, provider-managed), as shown in the accompanying table. The slight differences between Case Study #1 and #2 might reflect additional details or a different emphasis on the deployment process, but the core concepts remain consistent.  
![image](https://github.com/user-attachments/assets/5b5c7510-9969-432f-bb4a-01b19fe6880c)  
	Case Study #3 shifts focus to Cloud Service Models, specifically Infrastructure as a Service (IaaS), Platform as a Service (PaaS), and Software as a Service (SaaS). IaaS provides virtualized computing resources managed by the City of Vancouver (COV) Operations Team, with controlled access and privacy, suitable for on-premises use. PaaS offers a platform for application development and management, involving both COV and AWS Operations Teams, with configurable access and privacy in a remote setting. SaaS delivers software applications online, managed primarily by the COV Operations Team, with provider-managed access and privacy. The comparison table outlines how these models differ in school location, access, and confidentiality, distinguishing between the service layers.  
Regarding the tables, for Case Study #1 and Case Study #2, the tables compare the Private, Public, and Hybrid models. The "School - Location" row indicates that the Private model is on-premises, the Public model is remote, and the Hybrid model combines both. The "School - Access" row shows that the Private model has controlled access, the Public model offers developer access, and the Hybrid model provides configurable access. The "School - Privacy" row notes that the Private model has controlled privacy, the Public model has configurable privacy, and the Hybrid model is provider-managed. For Case Study #3, the table compares IaaS, PaaS, and SaaS models. The "School - Location" row indicates that IaaS is on-premises, PaaS is remote, and SaaS is online. The "School - Access" row shows that IaaS has controlled access, PaaS offers configurable access, and SaaS is provider-managed. The "School - Privacy" row states that IaaS has controlled privacy, PaaS has configurable privacy, and SaaS is provider-managed. These tables summarize the key differences across the models based on the visual data in the screenshots.  
# AWS Cost Analysis
![image](https://github.com/user-attachments/assets/1996773e-f928-4d68-aba0-2944ece21723)  
Case Study #4: Total Cost of Ownership - City of Vancouver examines the financial implications of cloud adoption for the City of Vancouver (COV). The background highlights challenges such as high initial costs, ongoing maintenance expenses, and the organization's scalability issues. The solution involves adopting AWS with a pay-as-you-go model, which reduces upfront investments, lowers maintenance costs, and improves flexibility and scalability. Specific results are not detailed in a table. Still, the focus is on achieving cost efficiency and operational benefits, suggesting a successful transition to a more economical cloud strategy for COV.  
![image](https://github.com/user-attachments/assets/57c11640-1b6b-48c6-9d31-0824ae32e973)  
Case Study #5: AWS Pricing Calculator provides a practical tool for cost estimation, featuring three export examples dated June 2023. Since the current date is June 2025, these estimates may not reflect the latest pricing or services available but offer a historical baseline. The exports likely include cost breakdowns for services such as Amazon EC2 (Elastic Compute Cloud), which provides virtual servers, and potentially other standard AWS services like Amazon S3 (Simple Storage Service) for storage or Amazon RDS (Relational Database Service) for databases. However, the specific services used are not fully legible in the image. The results imply that the calculator helps COV plan and optimize AWS expenses effectively, offering a structured approach to budgeting and resource allocation based on the exported data from June 2023, with the understanding that current 2025 pricing and service offerings may differ.  
![image](https://github.com/user-attachments/assets/7c8a9138-9a07-4d7e-b7be-e048e8720aac)  
Case Study #6: The Support Plan outlines a support strategy for the school department, and the Business Support Plan is selected. The justification notes that this plan offers 24/7 access to cloud support engineers, suitable for a school managing AWS. The result is a tailored support framework that ensures continuous assistance, enhancing operational reliability and addressing the specific needs of the educational environment within COV.  
# AWS Global infrastructure
![image](https://github.com/user-attachments/assets/5d7fdb22-a550-434f-8e00-4acfdfff8915)  
Case Study #7: AWS Global Infrastructure focuses on the global structure of AWS infrastructure utilized by the City of Vancouver (COV). The case study illustrates how AWS provides a distributed network of data centers and services managed by the COV Operations and AWS Operations teams. It highlights two main server instances, COV Virtual Server #1 and COV Virtual Server #2, located within the AWS Global Infrastructure, specifically in regions like Virginia and Oregon. The diagram includes Regional Edge Cache and Edge Location components, which enhance data delivery and accessibility. A student icon suggests that the infrastructure supports educational use cases, with the servers integrated with operational elements like CDN (Content Delivery Network) and MEC (Multi-access Edge Computing). The setup leverages AWS Data Centers and Global Infrastructure, with a COV Account overseeing the deployment.  
	The table in the case study compares three infrastructure components—Regional Edge Cache, Edge Location, and Region—across three criteria: School - Location, School - Access, and School - Privacy. The "School - Location" row indicates that Regional Edge Cache is distributed, Edge Location is at the edge, and Region is centralized, reflecting their geographical deployment strategies. The "School - Access" row shows that Regional Edge Cache offers limited access, Edge Location provides global access, and Region offers regional access, indicating the scope of availability for users. The "School - Privacy" row notes that Regional Edge Cache has enhanced privacy, Edge Location has shared privacy, and Region has controlled privacy, highlighting the varying levels of data protection across these components. These results demonstrate how AWS's global infrastructure supports COV's needs with a balance of accessibility and privacy tailored to different deployment layers.  
# AWS IAM
![image](https://github.com/user-attachments/assets/67515ccf-9df9-4b4e-9569-fca011870d71)  
	Case Study #8: Who is responsible outlines the shared responsibility model between the City of Vancouver (COV) and AWS for managing cloud resources. The diagram illustrates a COV Operational Environment within AWS Data Centers, with layers including EC2, Platform, and Software, managed by COV Operations Teams and AWS Operations Teams. The table delineates responsibilities: COV is responsible for Guest OS, applications, data, configuration, security settings, software security, updates, and content/user access (if applicable) across EC2, Platform, Software, and School layers. AWS is responsible for hardware, hypervisor, networking, infrastructure maintenance, and underlying environment security. The results clarify that COV handles application-level management and security. At the same time, AWS manages the physical and foundational infrastructure, ensuring a clear division of duties that enhances security and operational efficiency.  
![image](https://github.com/user-attachments/assets/6f2bf2c7-36f3-4e8e-a46e-97100e28266a)  
	Case Study #9: IAM practice: Lab 1 focuses on Identity and Access Management (IAM) practices through a lab exercise, evaluated with a total score of 40/40. The tasks involve adding users to groups and testing login and instance management capabilities. Task 2a added user-1 to the S3-Support group (5/5), Task 2b added user-2 to the EC2-Support group (5/5), and Task 2c added user-3 to the EC2-Admin group (5/5), successfully configuring user roles. Task 3a confirmed user-1 logged in (5/5), Task 3b confirmed user-2 logged in (5/5), Task 3c recorded user-2’s EC2 stop instance attempt (5/5), Task 3d confirmed user-3 logged in (5/5), and Task 3e recorded user-3’s EC2 stop instance attempt (5/5). The results indicate complete success in all tasks, demonstrating effective IAM configuration, user authentication, and instance management, achieving a perfect score.  
# AWS VPC
![image](https://github.com/user-attachments/assets/cb2290d7-2ff8-45dd-9fba-1d117e7d17a0)  
	Case Study #10: Build your VPC: Lab 2 is a hands-on lab exercise focused on building and configuring a Virtual Private Cloud (VPC) on AWS as part of the City of Vancouver's (COV) cloud training, achieving a total score of 30/30. The lab includes five successful tasks: Task 1 confirms the correct creation of a VPC (5/5), Task 2a verifies the proper setup of new subnets (5/5), Task 2b ensures subnet route table association (5/5), Task 3 validates the creation of a security group (5/5), and Task 4a and 4b confirm the correct creation and website accessibility of an EC2 instance (5/5 each), demonstrating effective network segmentation, traffic management, security, and instance deployment, highlighting COV's proficiency in managing a secure and functional cloud environment.  
# AWS Lambda
![image](https://github.com/user-attachments/assets/0925fc5f-0984-4b8f-983c-ce85005c8d31)  
	Case Study #11: Create an AWS Lambda function is a hands-on lab exercise focused on developing and configuring an AWS Lambda function as part of the City of Vancouver's (COV) cloud training, achieving a total score of 20/20. The lab includes four successful tasks: Task 1 confirms the creation of a Lambda function (5/5), Task 2 verifies the setup of a scheduled expression to automate the function (5/5), Task 3 ensures the Lambda function is configured correctly (5/5), and Task 4 demonstrates the function's ability to stop an instance (5/5), likely an EC2 instance, showcasing serverless computing capabilities. The results indicate complete success across all tasks, highlighting COV's proficiency in creating, scheduling, configuring, and utilizing AWS Lambda for automated instance management, achieving a perfect score.  
# AWS EBS
![image](https://github.com/user-attachments/assets/f62eee02-c7ab-49f5-b2c1-288b0c2dc607)  
	Case Study #12: Working with Amazon EBS: Lab 4 is a hands-on lab exercise focused on managing Amazon Elastic Block Store (EBS) as part of the City of Vancouver's (COV) cloud training, achieving a total score of 25/25. The lab includes six successful tasks: Task 1 confirms the creation of an EBS volume (5/5), Task 2 verifies the attachment of the volume to an instance (5/5), Task 4 ensures the volume is mounted (5/5), Task 5 demonstrates the creation of a snapshot (5/5), and Task 6 validates the restoration of the snapshot (5/5), with Task 3 missing but implied as part of the mounting process. The results indicate complete success across all tasks, showcasing COV's proficiency in creating, attaching, mounting, snapshotting, and restoring EBS volumes, highlighting effective storage management and data backup capabilities in AWS.
 







