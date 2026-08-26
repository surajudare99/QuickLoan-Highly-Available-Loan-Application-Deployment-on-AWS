# Project Execution Flow

1. Designed AWS Network Infrastructure
- Created VPC, Public & Private Subnets, Internet Gateway, NAT Gateway, and Route Tables.

2. Configured Security
- Implemented Security Groups for secure SSH, HTTP, and MySQL communication.

3. Deployed Compute Resources
- Launched Jump Server, Application Server, and Database Server.

4. Hosted the Application
- Installed Nginx, PHP, and PHP-FPM on EC2 and deployed the QuickLoan application.

5. Integrated Amazon S3
- Stored and served application images from S3.

6. Configured Amazon RDS MySQL
- Created database, tables, and connected the application to RDS.

7. Enabled Domain Access
- Configured No-IP Dynamic DNS and Nginx virtual host settings.

8. Validated Application Functionality
- Tested website access, image loading, form submission, and database entry creation.

9. Implemented High Availability
- Created AMI, Launch Template, Target Group, Application Load Balancer, and Auto Scaling Group.

10. Configured Monitoring & Alerts
- Set up CloudWatch alarms and SNS notifications for infrastructure monitoring.
