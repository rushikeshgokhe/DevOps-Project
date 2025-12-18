# Automated Static Website Deployment using Jenkins & AWS S3

## Project Overview
This project demonstrates a DevOps CI/CD pipeline that automates the deployment of a static website to Amazon S3 using Jenkins.

The pipeline was designed to reduce manual deployment effort and ensure continuous integration and continuous deployment.

## Tools & Technologies Used
- Jenkins
- AWS EC2
- Amazon S3
- IAM Roles & Policies
- Git & GitHub
- Linux
- Bash Scripting

## CI/CD Pipeline Workflow
1. Developer pushes code to GitHub repository
2. Jenkins automatically pulls the latest code
3. Build stage verifies the project files
4. Deployment stage uploads files to Amazon S3
5. Static website updates automatically

## Key DevOps Concepts Implemented
- CI/CD pipeline automation
- Jenkins pipeline scripting
- IAM role-based access
- Automated deployment
- Cost-aware cloud usage

## Cost Optimization Note
The Jenkins pipeline and AWS infrastructure were implemented and tested successfully.  
After validation, AWS EC2 and Jenkins resources were terminated to avoid ongoing cloud charges, as AWS is a paid service.

## Status
Completed (Infrastructure terminated after testing)
