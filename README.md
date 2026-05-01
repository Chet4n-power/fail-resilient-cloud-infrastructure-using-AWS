# fail-resilient-cloud-infrastructure-using-AWS
This is the open source repo of fail-resilient cloud infrastructure that is designed for apps (Here we used NGINX app which is very primitive) 
The design of the architecture is provided in architecture.png file
The main concepts we used throughout our project are AWS EC2 instances, Launch Templates, Load Balancers(Here Application Load Balancer), Auto Scaling Group, Target Groups etc....

<img width="893" height="521" alt="image" src="https://github.com/user-attachments/assets/33bb3cc6-ecb0-48e3-8c00-18ac87915639" />



Built a highly available and scalable web application infrastructure using AWS services to handle traffic fluctuations and ensure fault tolerance.
The system consists of multiple Linux-based EC2 instances running an Nginx web server, deployed behind an Application Load Balancer (ALB). Traffic is distributed across instances using the ALB, ensuring high availability and reliability.
An Auto Scaling Group (ASG) was configured to automatically maintain the desired number of instances, replacing unhealthy instances and ensuring continuous service availability during failures or load changes.
The infrastructure operates within a default VPC using public subnets to allow external access through the ALB.
