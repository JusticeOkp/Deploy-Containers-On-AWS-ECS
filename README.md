# Deploy Containers On AWS ECS

Create an ECS cluster with AWS Fargate and define a task using a public WordPress Docker image or a private ECR image. Deploy an ECS service with an Application Load Balancer for access. Set up an RDS MySQL instance for data storage and connect it to the WordPress application.

---

## **Features**

1. **ECS**
   - ECS cluster with AWS fargate
2. **WordPress docker**
   - Create a task definition with a WordPress docker public image or use a private container image from ECR
3. **Application load balancer**
   - Deploy an ECS service that will use an application load balancer which will be used to access the application. Access the application with ALB(Application Load balancer) DNS name.
4. **RDS MYSQL instance**
   - Create an RDS MYSQL instance with WordPress to store the application data. Connect the database with the application.
