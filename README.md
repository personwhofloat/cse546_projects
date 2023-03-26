# Autoscaling Image Classifier using AWS

## CSE 546: Cloud Computing Project 2

Group members:
| Name | Student ID | Task |
|------|------------|------|
|Truong Son Nguyen| 1225266250 | handler.py |
| Abhradeep Roy | ID | Task |
| Aman Jain| 1224726750 | configuration management & testing | 
 

<hr>

DynamDB Table name: `table-name`

S3 bucket names: `input-bucket-name` and `output-bucket-name`

<hr>

## Member Tasks
### Truong Son Nguyen - (ASU ID: 1225266250)
 - I am responsible for programming the handler.py file which takes events every time a user uploads a video to the input bucket and processes it to identify the student in such video. Then querying for the student's information from the DynamoDB database, parse it as a csv file and save to the output bucket.
 

### Abhradeep Roy – (ASU ID: ).
 - Task
### Aman Jain  -  (ASU ID: 1224726750)
 - I mainly focussed on setting up AWS configuration and required resources for the project. For instance, I configured the required IAM roles to run lambda function. Additionally, I created an ECR repository for the lambda function where the docker image is pushed. I created a script to dump student_data.json data to the DynamoDB table. Furthermore, I worked on creating S3 buckets for input and output. When the setup was complete, I along with Abhradeep performed end to end testing to check the whole flow. 

 
 <hr>
 






