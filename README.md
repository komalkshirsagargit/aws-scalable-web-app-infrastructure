# AWS Scalable Web Application Infrastructure

## Project Overview

This project demonstrates the deployment of a scalable and highly available web application infrastructure on AWS.

The infrastructure was designed using core AWS networking, compute, database, monitoring, and notification services to ensure availability, scalability, and operational visibility.

## AWS Services Used

- Amazon VPC
- Public and Private Subnets
- Internet Gateway
- NAT Gateway
- EC2
- Launch Templates
- Auto Scaling Group
- Application Load Balancer
- Target Groups
- Amazon RDS
- CloudWatch
- Amazon SNS

## Architecture

The infrastructure consists of:

- VPC for network isolation
- Public and Private Subnets
- Internet Gateway for public access
- NAT Gateway for outbound internet access from private subnets
- Application Load Balancer for traffic distribution
- Auto Scaling Group for high availability
- Amazon RDS for database storage
- CloudWatch for monitoring
- SNS for alert notifications

## Implementation Screenshots

### VPC Creation
![VPC Creation](VPC%20creation.png)

### Subnet Creation
![Subnet Creation](Subnet%20creation.png)

### Internet Gateway
![Internet Gateway](IGW%20creation.png)

### NAT Gateway
![NAT Gateway](NATgw%20creation.png)

### Security Groups
![Security Groups](SG%20creation.png)

### Launch Template
![Launch Template](Launch%20Template.png)

### Target Group
![Target Group](TG%20creation.png)

### Load Balancer
![Load Balancer](LB%20creation.png)

### Auto Scaling Group
![Auto Scaling Group](AS%20Group.png)

### RDS Database
![RDS Database](DB%20creation.png)

### SNS Topic
![SNS Topic](SNS%20Topic.png)

### CloudWatch Alarms
![CloudWatch Alarms](Threshold%20Alarms.png)

### Final Website Output
![Website Output](Sample%20Website%20Hosted.png)

## Project Objectives

- Deploy a scalable web application
- Configure secure networking using VPC
- Implement Auto Scaling
- Configure Load Balancer
- Deploy RDS database
- Monitor infrastructure using CloudWatch
- Receive alerts through SNS

## Project Status

Completed
