# ⚡️ Summary ⚡️

In this project, We'll be using the AWS Identity and Access Management ***(IAM)*** service to control who is ***(authenticated)*** (signed in) and ***(authorized)*** (has permissions) in your AWS account. 
We'll launch an EC2 instances, then control who has access to it by creating some ***(IAM policies)*** and ***(user groups)***. 

![Screen Shot 2025-05-26 at 3 32 22 PM](https://github.com/user-attachments/assets/cf917b76-e80c-445d-b2cc-a7ddd60ccd97)
- ***[Vulnerability Management Program Implementation](https://github.com/kiran-regmi/vulnerability-management-program)***

# Things we need to create: 
* 💻 EC2 instances 
* 🔖 AWS Account Alias 
* 📏 IAM Policies
* 👩‍👩‍👧‍👧 User Groups and IAM Users 


## Step 1 - Launch EC2 instances: 
* Login to AWS Managemnt Console https://signin.aws.amazon.com/signup?request_type=register.
* Open your EC2 console - search for it at the search bar.
![Screen Shot 2025-05-26 at 5 30 51 PM](https://github.com/user-attachments/assets/429e412f-1a82-4778-b4e6-062e1b707d8e)

![Screen Shot 2025-05-26 at 5 33 42 PM](https://github.com/user-attachments/assets/adf168e1-8042-4420-afc1-972f081e7b87)

![Screen Shot 2025-05-26 at 6 06 05 PM](https://github.com/user-attachments/assets/cc23306a-ddca-4179-9bc9-5f012d775b95)
* Switch your Region to the one closest to you.
* In your EC2 console, choose Launch instance.
* Enter the instance name. Ex: **intern-kiran-regmi-production**
* Choose Add additional tags, which is right next to your Name field.
* Enter resource type. Ex: **Console**
* Enter tag name (key value). Ex: **Env - Production**

![Screen Shot 2025-05-26 at 6 18 52 PM](https://github.com/user-attachments/assets/9ea2e5e3-92ad-4a41-a109-b663aa525f39)

**Application and OS Images (Amazon Machine Image)**
An AMI is a template that contains the software configuration (operating system, application server, and applications) required to launch your instance. Search or Browse for AMIs if you don’t see what you are looking for below
* Choose Amazon Linux 2023 AMI

![Screen Shot 2025-05-26 at 6 32 37 PM](https://github.com/user-attachments/assets/a4d16fbb-192d-435d-8a6f-1e7eb106dc45)

* Instance type - choose free tier t2micro
* Key Pair name - you can skip this for now

![Screen Shot 2025-05-26 at 6 43 08 PM](https://github.com/user-attachments/assets/5d9d5eac-10c2-4c62-8fc5-939bf1731e64)



## Step 2 - Create IAM Policies:

## Step 3 - Create User Groups and IAM Users:

## Step 4 - Check to See User Can Delete EC2 instance:

## Step 5 - Wrap Up:
