# CLOUD-STORAGE-CREATION-S3-AND-LAUNCHING-AN-EC2-INSTANCE-IN-AWS-

## NAME: Suchitra Nath
## REG NO: 212223220112

# Aim:
To create a Simple Storage Service (S3) in AWS and to launch an EC2 instance in AWS.

# Procedure
a) Steps to Create a first S3 Bucket:

Step 1: Sign in to the AWS Management Console Go to https://console.aws.amazon.com/s3. 

Step 2: Open the S3 Service In the console, type S3 in the search bar and select S3 to open the service dashboard. 

Step 3: Create Bucket Click the Create bucket button. 

Step 4: Configure Bucket Settings

• Bucket name: Choose a globally unique name. • AWS Region: Select the region where you want to store your data.

Step 5: Object Ownership Choose between: ▪ ACLs disabled (recommended) – Bucket owner has full control. ▪ ACLs enabled – Control access via access control lists.

Step 6: Block Public Access Settings By default, all public access is blocked. Leave it as-is unless you need public access. 

Step 7: Bucket Versioning (optional) Choose whether to enable versioning for objects in the bucket.

Step 8: Encryption (optional) Select encryption options (SSE-S3, SSE-KMS, or none). 

Step 9: Advanced Settings (optional) Add tags, configure logging, etc. 

Step 10: Create the Bucket Click Create bucket at the bottom of the page.

b) i. Steps to launch an EC2 Instance

Go to the EC2 Dashboard in AWS Console.

Click on “Launch Instance”.

Choose an Amazon Machine Image (AMI) (e.g., Amazon Linux).

Select an instance type (e.g., t2.micro for Free Tier).

Create or choose a key pair for SSH access.

Configure network settings (use default VPC/subnet).

Configure storage (default root volume is fine).

Review the settings and click “Launch Instance”.

Wait for the instance to enter the running state.

c) Step 3: Connect to Your Instance

• Linux: Use SSH command with your .pem key. • Windo Use RDP with decrypted admin password.ws:

d) Steps to Clean Up (Terminate the Instance)

Go to EC2 Instances.
Select your instance → Instance State → Terminate.

# Output:
# S3
## Bucket creating:


<img width="2559" height="1458" alt="Screenshot 2025-09-20 153620" src="https://github.com/user-attachments/assets/4ddfc0d7-56ab-4058-951b-4d64676b2bdf" />

## Folder Creation:

<img width="2559" height="1462" alt="Screenshot 2025-09-20 153559" src="https://github.com/user-attachments/assets/c6fcbf64-1d4e-4664-bcad-47abd5e4135a" />

## File Uploading:

<img width="2554" height="1529" alt="Screenshot 2025-09-20 153531" src="https://github.com/user-attachments/assets/6ea7e414-9ae3-4b05-885e-9149be924cc7" />

# EC2
## Creating Instance:

<img width="2558" height="1529" alt="Screenshot 2025-09-20 153827" src="https://github.com/user-attachments/assets/bcf7392e-62ac-4dfe-bd75-53d6679e30d1" />

## Launched Instance:

<img width="2556" height="1530" alt="Screenshot 2025-09-20 154253" src="https://github.com/user-attachments/assets/f560fb78-3ec6-4bd0-bb3f-ab9717933d1f" />

# Result:
Thus, a Simple Storage Service (S3) and EC2 (Elastic Compute Cloud) - instance has been successfully created and launched in AWS
