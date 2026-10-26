# AWS-Monitoring-and-Alerting-Platform-Using-CloudFormation-Nested-Stacks

Project Overview

Designed and deployed an end-to-end monitoring and alerting solution on AWS using CloudFormation Nested Stacks. The project provisions a custom VPC, Public Subnet, Internet Gateway, Route Table, Security Group, Ubuntu EC2 Instance, SNS Topic, Email Subscription, and CloudWatch Alarm. The infrastructure is organized into separate Networking, Compute, Notification, and Monitoring stacks, demonstrating modular Infrastructure as Code (IaC) design principles.

Key Features
Built using CloudFormation Nested Stacks
Custom VPC and networking components
Ubuntu EC2 Monitoring Server
SNS Topic with Email Notifications
CloudWatch Alarm for CPU Monitoring
Cross-stack communication using Outputs and Parameters
Infrastructure fully automated through CloudFormation
Architecture Flow

EC2 Instance → CloudWatch Metric → CloudWatch Alarm → SNS Topic → Email Notification

Testing Performed
Successfully deployed all Nested Stacks using CloudFormation
Verified EC2 instance creation and SSH connectivity
Confirmed SNS Email Subscription
Generated CPU load using the Stress utility
Triggered CloudWatch Alarm when CPU Utilization exceeded 80%
Received Email Notification through SNS
AWS Services Used
Amazon VPC
Amazon EC2
Amazon SNS
Amazon CloudWatch
AWS CloudFormation
Internet Gateway
Route Tables
Security Groups
Skills Demonstrated

CloudFormation, Infrastructure as Code (IaC), Nested Stacks, VPC Design, EC2 Administration, CloudWatch Monitoring, SNS Notifications, AWS Networking, Alerting Solutions, Parameter Passing, Stack Outputs, and Infrastructure Automation.

Outcome

Successfully built, deployed, and validated a complete monitoring and alerting platform that automatically detects high CPU utilization on an EC2 instance and sends email notifications using CloudWatch and SNS.
