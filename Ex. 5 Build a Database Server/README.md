# Lab 5 – Build a Database Server (AWS)

## Author

* **Name**: BHARATH B
* **Register Number**: 212224060041
* **Date of Submission**: 17-03-2026

---

## Objective

The objective of this experiment is to understand how to deploy and configure a database server in AWS. This lab focuses on launching an EC2 instance, installing a database management system (DBMS), configuring basic database settings, creating a sample database, and validating connectivity to the database server.

---

## Prerequisites

* Basic understanding of cloud computing concepts
* AWS account or AWS Academy Lab access
* An existing VPC and EC2 knowledge (from previous labs)
* Basic knowledge of Linux commands and SQL

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Security Groups
* SSH Client (Terminal / PuTTY)
* MySQL / MariaDB / PostgreSQL (any one)

---

## Tasks Performed

### Task 1: Launch EC2 Instance for Database Server

Launch a new EC2 instance using Amazon Linux 2 AMI. Select an appropriate instance type and configure key pair and security group.

---

### Task 2: Configure Security Group for Database Access

Modify the security group to allow:

* SSH (Port 22) for remote access
* Database port (e.g., MySQL – 3306 or PostgreSQL – 5432)

---

### Task 3: Connect to EC2 Instance

Connect to the EC2 instance using SSH from your local machine.

---

### Task 4: Install Database Server

Install a database server software such as MySQL, MariaDB, or PostgreSQL on the EC2 instance using package manager commands.

---

### Task 5: Start and Configure Database Service

Start the database service and configure basic settings such as root password and user privileges.

---

### Task 6: Create a Sample Database

Create a sample database and a table inside it. Insert a few records into the table.

---

### Task 7: Test Database Connectivity

Test the database server by connecting to it locally or remotely and performing basic SQL queries.

---

## Workflow (Student Explanation)

(Write the steps you followed in your own words)

1. Create a Security Group for the RDS DB instance
2. Create a DB Subnet Group
3. Create an Amazon RDS DB instance
4. Interact with your database

---

## Output Screenshots (Attach 3)

### Screenshot 1: EC2 Instance for Database Server

<img width="1920" height="1200" alt="Screenshot 2026-03-09 101928" src="https://github.com/user-attachments/assets/43a74809-2440-4eac-897c-0238789d1399" />

---

### Screenshot 2: Database Service Running

<img width="1920" height="1200" alt="Screenshot 2026-03-09 102252" src="https://github.com/user-attachments/assets/c42b2b08-d1a5-4ed2-910a-503623527223" />
<img width="1920" height="1200" alt="Screenshot 2026-03-09 104454" src="https://github.com/user-attachments/assets/1659b99c-610d-4695-8d39-729253e57741" />

---

### Screenshot 3: Sample Database and Table

<img width="1920" height="1200" alt="Screenshot 2026-03-09 110951" src="https://github.com/user-attachments/assets/388c7518-dc1b-4bea-bc6d-36fdee1c18e4" />

---

## Result

This experiment demonstrated how to build a database server in AWS using an EC2 instance. By installing and configuring a DBMS, creating a sample database, and testing connectivity, the fundamentals of hosting and managing a cloud-based database server were underst
