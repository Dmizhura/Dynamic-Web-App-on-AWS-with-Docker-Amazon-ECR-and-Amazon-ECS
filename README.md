Dynamic Web App on AWS with Docker, Amazon ECR, and Amazon ECS
This project is a comprehensive DevOps initiative aimed at hosting a dynamic web application on Amazon Web Services (AWS). Below is an outline of the resources utilized along with a brief description of their roles in the deployment process.

Resources Utilized
Docker: Used to build the container image for the web application.
Git: Employed for version control to track changes to source code and files.
GitHub: Used to manage Dockerfiles and application code in Git repositories.
AWS CLI: Enabled interaction with AWS services via the command line.
Flyway: Utilized for migrating SQL data into the Amazon RDS database.
Visual Studio Code (VS Code): Chosen as the integrated development environment for writing and editing scripts.
Amazon ECR (Elastic Container Registry): Utilized for storing the Docker image.
Amazon ECS (Elastic Container Service): Used to containerize the web application on the AWS cloud.
3 Tier VPC (Virtual Private Cloud): Configured with public and private subnets across two availability zones.
Internet Gateway: Facilitated communications between VPC resources and the internet.
NAT Gateway: Enabled resources in private subnets to access the internet.
Amazon RDS (Relational Database Service): Utilized for the relational database.
ECS Fargate: Deployed to run the containerized application.
Application Load Balancer: Utilized for distributing web traffic to ECS Fargate tasks.
Auto Scaling Group: Dynamically created new ECS tasks as required.
Route 53: Registered domain names and created record sets for DNS management.
Amazon S3: Stored files and container environment variables.
IAM Role: Granted permissions for ECS to execute tasks.
Bastion Host: Utilized for setting up an SSH tunnel.
Security Groups: Controlled inbound and outbound traffic to resources.
Certificate Manager: Employed for encrypting data in transit.
