# Dockerfile for Jenkins Data Volume Container
FROM Jenkins
VOLUME ["/var/jenkins_home"]
# Creating a Jenkins Data Volume
docker build -t jenkins_dv .
#Tag the jenkins_dv image
docker tag jenkins_dv:latest 2284-8094-5348.dkr.ecr.us-east-1.amazonaws.com/jenkins_dv:latest
# Push the jenkins-dv image to ECR
docker push 2284-8094-5348.dkr.ecr.us-east-1.amazonaws.com/jenkins_dv:latest
