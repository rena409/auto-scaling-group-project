# auto-scaling-group-project
This project demonstrate how to deploy high avaliable and scaling the web application on using EC2AUTO SCALING GROUP,classic load balancer or application load balancer, SNS notification and VPC configuration.
# Project Overview
# Goal- To automatically scale EC2 instances based on demand and ensure high availability with load balaner
# Key AWS services used:
 VPC (Virtual Private Cloud)
 EC2 (Elastic Compute Cloud)
 Load Balancer (Classical and application)
 Auto Scaling Groups
 Simple notification services (SNS)
 Security Groups
# Learning Outcomes:
Understanding Auto Scaling Group Concepts
Understanding the Scaling policies and health checks
Practical Experience Creating an ASG
To know the use of Load Balancer
Knows the use of SNS (Simple Notification Service)
VPC uses & manage/edit security groups also NACL
Create instances with additional data 
# Documentation 
Amazon EC2 Auto Scaling Group (ASG) is a service that automatically manages the number of EC2 instances running in your AWS environment.
# Steps to Create Auto Scaling Group
STEP 1 :- We need to create a VPC (virtual private cloud )
STEP 2 :- Change the inbound & outbond rules of security groups, which is attach with the existing VPC
STEP 3 :- We create a instance
STEP 4 :- Create image & template with the help of existing instance
STEP 5 :- Then create a load balancer (we create classic Load balancers
STEP 6 :- Create a Simple Notification Service topic and create a subscription with the help of existing topic
STEP 7 :- Now we create a Auto Scaling Group













