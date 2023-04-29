# Autoscaling Image Classifier using AWS

## CSE 546: Cloud Computing Project 3

Group members:
| Name | Student ID | Task |
|------|------------|------|
|Truong Son Nguyen| 1225266250 | Documentation |
| Abhradeep Roy | 1224961634 | Openstack installation and Testing  |
| Aman Jain| 1224726750 | Openstack installation, Testing and Aws configuration | 
 

<hr>

DynamDB Table name: `student`

S3 bucket names: `input-video-bkt` and `output-video-bkt`
SQS queues: `input-queue` and `output-queue`

<hr>

## Member Tasks
### Truong Son Nguyen - (ASU ID: 1225266250)
 - I am responsible for documenting the project and help other with seting up OpenStack VM
 
### Abhradeep Roy – (ASU ID: 1224961634).
 - I worked along with Aman and was responsible for installing the openstack, configuring the openstack so that it can speak with the external IP using the floating IP and the DNS server configuration. We also took care of the testing and evaluation part of the project.
 
### Aman Jain  -  (ASU ID: 1224726750)
 - I worked along with Abhradeep Roy to setup openstack on EC2 instance from scratch. Additionally, I created the script on openstack server to poll both input, output queues and trigger lambda function whenever a message arrives. Apart from this, the script also displays student information on the openstack terminal. Furthermore, I worked on setting up and linking  buckets, SNS, SQS. I also replicated the Lambda setup from project 2 in a new AWS account. Finally, we did a load test to verify our functionality. 
 
 <hr>
 






