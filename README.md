<h3 align ="left"> Deploying Wordpress on AWS using EC2</h3>

Introduction
Prerequisites
What is EC2?
Step 1: Create and Configure the VPC
Step 2: Create a Subnet
Step 3: Create an Internet Gateway
Step 4: Create a Route Table
Step 5: Create EC2 Instance with Public IP
Step 6: Configuring Security Groups during EC2 Setup
Step 7: Connect to the EC2 Instance
Step 8: Install Nginx
Step 9: Install PHP MySQL
Step 10: Install MariaDB 10.5 on Amazon Linux using the Default Repo
Step 11: Log in to MariaDB as the Root User and Create a Database and User for WordPress
Step 12: Nginx Configuration for WordPress and Setting the EC2 Public IP Address
Step 13: Completed the WordPress Installation
Clean up
Introduction 🌟
Hosting WordPress on AWS EC2 allows you to leverage the scalability, reliability, and security of Amazon Web Services. This guide will go through the key AWS concepts such as EC2, VPC, subnet, route table, and security group, and how they all interlink to create a secure and scalable environment for your application.

Prerequisites ✅
AWS Account
Basic understanding of networking concepts
Familiarity with the AWS Management Console
What is EC2? 🤔
Amazon Elastic Compute Cloud (EC2) is a web service provided by Amazon Web Services (AWS) that allows users to rent virtual servers (referred to as "instances") on which they can run their applications. EC2 instances are essentially virtual machines that can be launched in the cloud and scaled up or down as needed.
