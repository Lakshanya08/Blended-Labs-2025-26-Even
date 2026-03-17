# Lab 6 – Scale and Load Balance Your Architecture

## Title

Scale and Load Balance Your Architecture

Author : LAKSHANYA.N

Reg no : 2122242030136

Date : 15-03-2026

---

## Objective

The objective of this lab is to understand how to design a scalable and highly available architecture on AWS using Auto Scaling and Elastic Load Balancing. This experiment focuses on distributing incoming traffic across multiple EC2 instances, automatically scaling resources based on demand, and validating fault tolerance.

---

## Prerequisites

* Basic knowledge of Amazon EC2 and VPC
* Completion of previous labs (IAM, EC2, EBS, Database Server)
* AWS Academy Lab access
* Stable internet connection

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Elastic Load Balancer (ELB / ALB)
* Auto Scaling Groups (ASG)
* Amazon CloudWatch

---

## Tasks Performed

### Task 1: Review Existing Architecture

Students review the existing EC2-based application architecture created in previous experiments.

### Task 2: Create a Launch Template

Students create a launch template that defines the EC2 instance configuration including AMI, instance type, security group, and user data.

### Task 3: Create an Auto Scaling Group

Students create an Auto Scaling Group using the launch template and configure minimum, maximum, and desired instance capacity.

### Task 4: Configure an Application Load Balancer

Students create an Application Load Balancer and configure target groups for routing traffic to EC2 instances.

### Task 5: Register Auto Scaling Group with Load Balancer

Students attach the Auto Scaling Group to the target group of the load balancer.

### Task 6: Configure Scaling Policies

Students configure scaling policies based on CPU utilization using Amazon CloudWatch alarms.

### Task 7: Test Load Balancing and Scaling

Students test the setup by generating traffic and observing automatic scaling and load distribution.

---

## Workflow (To be filled by Student)

1.Launch multiple servers.

2.Deploy the application on each server.

3.Create a load balancer.

4.Add servers to the load balancer.

5.Configure auto-scaling.

6.Test load distribution.

---

## Output Screenshots 
<img width="1917" height="1022" alt="Screenshot 2026-03-12 202806" src="https://github.com/user-attachments/assets/5712728c-29a1-4abc-bba8-ff3ee64b5d91" />
<img width="1918" height="957" alt="Screenshot 2026-03-12 213938" src="https://github.com/user-attachments/assets/eb70ad4b-c09e-4fa5-a54c-f4e2f1464591" />
<img width="1919" height="951" alt="Screenshot 2026-03-12 214755" src="https://github.com/user-attachments/assets/a6e863e8-890a-4ad0-9548-cab57381ab95" />
<img width="1913" height="968" alt="Screenshot 2026-03-12 220134" src="https://github.com/user-attachments/assets/db2a7ec9-aba0-4a2c-aaf7-37d2e21fc717" />
<img width="1919" height="965" alt="Screenshot 2026-03-12 211726" src="https://github.com/user-attachments/assets/435ca21a-356d-47b1-9542-64d56cb61a15" />
<img width="1913" height="968" alt="Screenshot 2026-03-12 220134" src="https://github.com/user-attachments/assets/c16ec7d7-438e-42a4-8a89-52fd6cce29d8" />


---


## Result

This experiment demonstrated how to build a scalable and fault-tolerant cloud architecture using Auto Scaling Groups and Elastic Load Balancing. The system automatically adjusted resources based on workload and ensured continuous service availability by distributing traffic across multiple instances.
