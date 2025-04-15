 # CREATE S3 BUCKET AND EC2 INSTANCES FOR LINUX AND WINDOWS
  ## AIM
To Create S3 bucket and EC2 Instances for Linux and Windows.
## PROBLEM STATEMENT
This experiment aims to demonstrate the creation of an Amazon S3 bucket for storage purposes and the setup of EC2 instances for both Linux and Windows operating systems using AWS. Amazon S3 (Simple Storage Service) provides secure and scalable object storage, while EC2 (Elastic Compute Cloud) allows users to deploy virtual servers for computation and application hosting.
## ALGORITHM
### Steps 1:
 **Login to AWS Management Console:**
1. Open the AWS Management Console.
2. Navigate to the **S3** service for bucket creation and **EC2** for instance setup.

 ### Steps 2:
**Create an S3 Bucket:**
1. Go to the S3 service.
2. Click on **Create bucket**.
3. Provide a unique **Bucket Name** and select the **Region**.
4. Configure additional settings as per requirements and click **Create bucket**.
 
 ### Steps 3:
 **Launch EC2 Instance (Linux):**
1. Go to the EC2 service.
2. Click **Launch Instance**.
3. Select an **Amazon Machine Image (AMI)**, such as Amazon Linux 2.
4. Choose an **Instance Type** (e.g., t2.micro).
5. Configure instance settings, key pair, and security groups, then **Launch** the instance.

 ### Steps 4:
 **Launch EC2 Instance (Windows):**
1. Repeat the EC2 launch steps but select a **Windows Server AMI**.
2. Complete instance configuration and **Launch**.
 
 ### Steps 5:
 **Connect to Instances:**
1. **Linux Instance**: Use SSH to connect.
   ```bash
   ssh -i "key_pair.pem" ec2-user@<linux_public_dns>

## COMMANDS

### S3 Bucket Creation
#### 1.AWS CLI Command:
aws s3 mb s3://<your-bucket-name> --region <your-region>
## EC2 Instance (Linux) Commands
Launch Linux EC2 instance and set up SSH access.
## EC2 Instance (Windows) Commands
Launch Windows EC2 instance and connect using RDP.

## OUTPUT
### REG NUMBER:212223220105
### NAME:SHANMUGAKARTHIK G

#### S3 buckets:
![image](https://github.com/user-attachments/assets/2320b883-64b8-45e4-aa70-cb3499a029d4)
![image](https://github.com/user-attachments/assets/25559cac-fc7f-4ef6-a1be-16dbc8775267)


#### EC2:
![creation of linux machine](https://github.com/user-attachments/assets/1690bd8a-bf80-40a3-94f0-5cb249834f79)

![creation of windows machine](https://github.com/user-attachments/assets/68bf1fc0-31da-4fe3-965c-93b5eeede6db)


 
## RESULT
 Thus ,The experiment to create an S3 bucket and launch EC2 instances for Linux and Windows is successfully completed.

  


