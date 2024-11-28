 # CREATE S3 BUCKET AND EC2 INSTANCES FOR LINUX AND WINDOWS
  ## AIM
       To Create S3 bucket and EC2 Instances for Linux and Windows.
## PROBLEM STATEMENT   
This experiment demonstrates the process of setting up cloud infrastructure on AWS by creating an S3 bucket for storage and EC2 instances to host Linux and Windows environments. The goal is to provide an overview of how to configure and interact with these resources effectively, along with commands and screenshots to document the process.

## ALGORITHM
 ### Steps 1:
 Log in to AWS Console
 ### Steps 2:
 Navigate to the S3 service. Click on Create bucket. Enter a Bucket name and select a Region. Configure Bucket settings as required (e.g., versioning, public access). Click on Create bucket to finalize.
 ### Steps 3:
 Go to the EC2 service. Click on Launch Instance. Select an Amazon Machine Image (AMI) for Linux (e.g., Amazon Linux 2). Choose an Instance Type (e.g., t2.micro for free tier). Configure Instance Details, Storage, and Security Group. Review and click Launch with a key pair (or create one if needed).
 ### Steps 4:
 Return to the EC2 service and click Launch Instance. Select a Windows AMI (e.g., Windows Server 2019). Choose the Instance Type. Configure Instance Details, Storage, and Security Group. Review and launch with a key pair (for future login).
 ### Steps 5:
 Verify the status of both instances in the EC2 dashboard. Connect to the Linux instance using SSH. Connect to the Windows instance using RDP.

## OUTPUT
s3bucket 
![s3](https://github.com/user-attachments/assets/38316f6a-ba18-4d37-94c3-d3bfb6aacfdd)
EC2 INSTANCE(WINDOWS)
![ec2](https://github.com/user-attachments/assets/298d7a0c-3f21-4d4f-a025-1f7df96b6de8)
![ec22](https://github.com/user-attachments/assets/da0bae43-f881-4593-a369-45052bc5f8c0)

 
## RESULT
Successfully created an S3 bucket and EC2 instances for both Linux and Windows, demonstrating cloud resource management on AWS. 

  


