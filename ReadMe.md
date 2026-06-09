## Build a Database Server (AWS)
## Name: AISHWARYA V
## Register Number: 212223220003
## Objective
The objective of this experiment is to understand how to deploy and configure a database server in AWS. This lab focuses on launching an EC2 instance, installing a database management system (DBMS), configuring basic database settings, creating a sample database, and validating connectivity to the database server.

## Prerequisites
Basic understanding of cloud computing concepts
AWS account or AWS Academy Lab access
An existing VPC and EC2 knowledge (from previous labs)
Basic knowledge of Linux commands and SQL

## Tools Used
AWS Management Console
Amazon EC2
Security Groups
SSH Client (Terminal / PuTTY)
MySQL / MariaDB / PostgreSQL (any one)

## Tasks Performed
Task 1: Launch EC2 Instance for Database Server
Launch a new EC2 instance using Amazon Linux 2 AMI. Select an appropriate instance type and configure key pair and security group.

Task 2: Configure Security Group for Database Access
Modify the security group to allow:

SSH (Port 22) for remote access
Database port (e.g., MySQL – 3306 or PostgreSQL – 5432)
Task 3: Connect to EC2 Instance
Connect to the EC2 instance using SSH from your local machine.

Task 4: Install Database Server
Install a database server software such as MySQL, MariaDB, or PostgreSQL on the EC2 instance using package manager commands.

Task 5: Start and Configure Database Service
Start the database service and configure basic settings such as root password and user privileges.

Task 6: Create a Sample Database
Create a sample database and a table inside it. Insert a few records into the table.

Task 7: Test Database Connectivity
Test the database server by connecting to it locally or remotely and performing basic SQL queries.

## Workflow (Student Explanation)
1.Launch an EC2 instance using Amazon Linux 2 AMI and select a suitable instance type. Configure key pair and security group to prepare the instance for database server deployment.
2.Modify the Security Group to allow:
SSH (Port 22) for remote login

Database port (3306 for MySQL / 5432 for PostgreSQL) This ensures secure access to the database server.

3.Connect to the EC2 instance using SSH and install a database server such as MySQL, MariaDB, or PostgreSQL using package manager commands.
4.Start the database service, configure root credentials, and set user privileges. Create a sample database, table, and insert records to prepare the system for usage.
5.Test the database by connecting locally or remotely and executing basic SQL queries. This confirms that the database server is functioning correctly.

## Output Screenshots (Attach 3)
Screenshot 1: EC2 Instance for Database Server
<img width="1919" height="896" alt="564705275-3e85a74c-ba9f-4e64-93fb-fb4032bef237" src="https://github.com/user-attachments/assets/b645472f-e526-47e4-b7b0-6082799fe912" />

Screenshot 2: Database Service Running
<img width="1919" height="906" alt="564705390-0317ae7e-65d2-4d98-8d09-68d36856113f" src="https://github.com/user-attachments/assets/a8ed0a23-d1e2-4334-bc5d-204ca608d6ad" />

Screenshot 3: Sample Database and Table
<img width="1916" height="957" alt="564705658-26258aa8-cb2f-4502-b2ec-46d502df82a8" src="https://github.com/user-attachments/assets/84236184-06b6-4b52-be46-22703c5c4564" />

## Result
This experiment demonstrated how to build a database server in AWS using an EC2 instance. By installing and configuring a DBMS, creating a sample database, and testing connectivity, the fundamentals of hosting and managing a cloud-based database server were understanding..
