# AWS_Cloud_Architecting_MedicalCompany

As cloud architects, we are expected to:
1. Design an infrastructure architecture in Amazon Web Services (AWS) to meet application needs of Medical Company
2. Connect doctor and users/patients
# Executive Summary
Given to us that the Medical Company is a startup software as a service (SaaS) company which has built an online medical social networking and diagnosis assistance application for users in APAC, the US, and Europe. The application intends to allow online appointments, remote consultation, remote diagnosis, electronic prescription transfer, and payment services. Additionally, allow customers to upload documents and images. Text would be extracted from documents, and images converted into multiple formats. The application has not yet been launched publicly. 
Presently, it uses a third-party server to host the medical company for deploying its current development and test infrastructure. It is based on Microsoft Windows server to host its web application and it is linked to Microsoft SQL server. It is expected from the cloud architects who are deploying the cloud solution to be built for business continuity. If one of the servers is unavailable, another one replaces the former. Next, we address the above tasks by:

•	Amazon EC2 in Auto Scaling groups for its web application.
•	Amazon RDS with MySQL for storing data.
•	Amazon S3 to store backups and the storing the uploaded file
•	Amazon ElastiCache to improve performance of their web applications. 
•	Elastic Load Balancing to distribute traffic across applications.
•	Amazon SNS for internal applications 
•	Amazon Cloud Watch for monitoring the system and maintaining the logs and notify other services to handle the issues arise in the system.
To conclude, build highly available platform on AWS which assists:
•	Making Online Appointments
•	Remote Consultation & Diagnosis
•	E- Prescription
•	Payment Service

# Requirements & Assumptions Throughout the Model 

The cloud architects intend on constructing a well architected framework which fulfills the following requirements:
•	High Availability
•	Scalability
•	Backup
•	Security
•	Upload supporting documents
•	Multi location support (Asia Pacific, Europe and USA)
•	Monitor

