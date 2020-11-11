# Elastic Container Service

Helps to run docker on the machines

ECS CORE: Running ECS on user-provisioned EC2 instances
Fargate: Running ECS takes on aws-provisioned compute (serverless)
EKS: Running ECS on AWS provisioned kubernetes (EC2 powered)
ECR: Docker container registry hosted by AWS (to store images)caching
ECS Cluster: Set of EC2 instances


ALB has a direct integration feature with ECS using port mapping. This allows to run multiple instances of same app on same EC2 (Cant do with Classic Loab Balancer)

Configure ecs on ec2 to:
- Assign to ecs cluster
- pull images from private registeries
- cloudwatch container logging
- iam roles for ecs tasks
