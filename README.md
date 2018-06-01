# aws_ecs (Elastic Container Service)

* All files are from AWS Cloud Developer Association (2018) course of Linuxacademy Ltd by Fernando Medina Corey. (5-start course!!)

## Deploy a python flask application with AWS ECS
* EC2 instance as workstation to interact with Service and resource in AWS.
* Connect with AWS ECR (Elastic Container Register) and ECS.
* All application files are installed as container images to store in AWS ECR with Docker.
* ECS will interact with the images which is deployed in ECR.
* The container images will be sent through ECS upto another EC2 instance.
* Visit the public IP of the EC2 instance then the website application shows.

## Commands used for this project.
### Environment setup
```
sudo yum update -y
```

```
sudo yum install -y docker
```
