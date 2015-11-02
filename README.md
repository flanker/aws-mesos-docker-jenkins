# AWS Mesos Docker Jenkins

This repo demonstrates how to setup a Mesos cluster, and a Jenkins build server in AWS (Amazon Web Service) using CloudFormation. When a build job is triggered in Jenkins Master, Jenkins Master will ask Mesos to create a Jenkins Slave dynamically in Docker container and run build in the container.

## Current topology

## Target topology

## How to use it

## TODO list

- [ ] Complete this README;
- [ ] Setup the Jenkins Mesos plugin within the User Data for Jenkins Master in  cloudformation template;
- [ ] Update the InstanceSecurityGroup to only allow required ports;
- [ ] Remove public IP from instances. (They should be only accessible via load balancer. But this needs a NAT instance so internal instances could download packages from Internet)
