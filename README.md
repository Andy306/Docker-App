# Docker-App
Containerized Application with Docker & AWS Elastic Beanstalk
This project demonstrates deploying a Dockerized application to AWS Elastic Beanstalk, providing a scalable and resilient infrastructure. This README outlines the setup, deployment, and integration of AWS architecture pillars.

Project Overview
Docker Installation & Setup: Installing Docker locally to build and run containerized applications.
Custom Docker Image: Created a Dockerfile to define the application environment and dependencies.
Local Testing: Run the application container locally for testing.
Deployment to AWS Elastic Beanstalk: Deploy the containerized application on AWS Elastic Beanstalk for easy scaling and management.

Prerequisites
Docker: Install Docker to create and run containers locally.
AWS CLI: Set up the AWS Command Line Interface for deploying the application.
Elastic Beanstalk CLI: Required to deploy and manage your application on Elastic Beanstalk.

AWS Architecture Pillars
This project aligns with the AWS Well-Architected Framework.

 Security
IAM Roles and Permissions: Configured AWS Identity and Access Management (IAM) roles for controlled access to Elastic Beanstalk and other AWS services.
Environment Isolation: Elastic Beanstalk environments provide isolation, preventing unauthorized access to application resources and data.
Data Encryption: AWS services support encryption both in transit and at rest, which is implemented for any sensitive data transfers.
   
