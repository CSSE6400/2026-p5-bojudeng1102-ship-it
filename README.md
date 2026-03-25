TaskOverflow Deployment

Project Overview

This project deploys the TaskOverflow application to AWS using Terraform.
The application is containerised using Docker and runs on AWS ECS (Fargate), with a PostgreSQL database hosted on AWS RDS.


Technologies Used
1.Python (Flask)
2.Docker
3.Terraform
4.AWS ECS (Fargate)
5.AWS RDS (PostgreSQL)
6.AWS ECR

How to Run Locally
http://localhost:6400

Deployment (Terraform)
Initialise Terraform: terraform init
Apply configuration: terraform apply

Accessing the Application
After deployment, open:http://18.212.168.138:6400/

Project Structure
todo/ - Flask API code
main.tf - Terraform configuration
Dockerfile - Docker build file

Environment Variables
SQLALCHEMY_DATABASE_URI - Database connection string

Notes
Ensure Docker is running before building images
AWS credentials must be configured