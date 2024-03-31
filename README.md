![Alt text](docker project.jpg)
# Dynamic Web App on AWS with Docker, Amazon ECR, and Amazon ECS

This project is a comprehensive DevOps initiative aimed at hosting a dynamic web application on Amazon Web Services (AWS). Below is an outline of the resources utilized along with a brief description of their roles in the deployment process.

## Resources Utilized

1. **Docker**: Used to build the container image for the web application.
2. **Git**: Employed for version control to track changes to source code and files.
3. **GitHub**: Used to manage Dockerfiles and application code in Git repositories.
4. **AWS CLI**: Enabled interaction with AWS services via the command line.
5. **Flyway**: Utilized for migrating SQL data into the Amazon RDS database.
6. **Visual Studio Code (VS Code)**: Chosen as the integrated development environment for writing and editing scripts.
7. **Amazon ECR (Elastic Container Registry)**: Utilized for storing the Docker image.
8. **Amazon ECS (Elastic Container Service)**: Used to containerize the web application on the AWS cloud.
9. **3 Tier VPC (Virtual Private Cloud)**: Configured with public and private subnets across two availability zones.
10. **Internet Gateway**: Facilitated communications between VPC resources and the internet.
11. **NAT Gateway**: Enabled resources in private subnets to access the internet.
12. **Amazon RDS (Relational Database Service)**: Utilized for the relational database.
13. **ECS Fargate**: Deployed to run the containerized application.
14. **Application Load Balancer**: Utilized for distributing web traffic to ECS Fargate tasks.
15. **Auto Scaling Group**: Dynamically created new ECS tasks as required.
16. **Route 53**: Registered domain names and created record sets for DNS management.
17. **Amazon S3**: Stored files and container environment variables.
18. **IAM Role**: Granted permissions for ECS to execute tasks.
19. **Bastion Host**: Utilized for setting up an SSH tunnel.
20. **Security Groups**: Controlled inbound and outbound traffic to resources.
21. **Certificate Manager**: Employed for encrypting data in transit.

## Project Files
- **Deployment Scripts**: Available in the repository

## Contributing
Contributions to improve this project are welcome. Please submit a pull request.
