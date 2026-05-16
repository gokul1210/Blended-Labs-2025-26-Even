# Lab 1 - Introduction to AWS Identity and Access Management (IAM)

## Title
Introduction to AWS Identity and Access Management (IAM)


## Objective
The objective of this lab is to understand how AWS Identity and Access Management (IAM) controls authentication and authorization in AWS. The lab focuses on exploring IAM users and groups, analyzing attached policies, assigning users to appropriate groups based on organizational roles, and validating permissions by testing service access.


## Prerequisites
- Basic understanding of cloud computing concepts  
- AWS Academy Lab access  
- Web browser with internet connectivity  


## Tools Used
- AWS Management Console  
- AWS Identity and Access Management (IAM)  
- Amazon EC2  
- Amazon S3  


## Tasks Performed

### Task 1: Explore IAM Users and Groups
- Reviewed pre-created IAM users: user-1, user-2, user-3  
- Explored IAM groups: EC2-Admin, EC2-Support, S3-Support  
- Inspected managed and inline policies attached to groups  

<img width="940" height="538" alt="image" src="https://github.com/user-attachments/assets/fd430dd1-7673-4fe9-95f4-b8fab3c4b976" />
<img width="940" height="534" alt="image" src="https://github.com/user-attachments/assets/8846335d-cbd2-4ee5-8fd7-1cf964b51092" />
<img width="940" height="534" alt="image" src="https://github.com/user-attachments/assets/48f4dd36-6e33-4149-ac42-c5bf7b2378a2" />



### Task 2: Add Users to Groups
- Added user-1 to the S3-Support group  
- Added user-2 to the EC2-Support group  
- Added user-3 to the EC2-Admin group  
**Screenshot:**  

<img width="940" height="538" alt="image" src="https://github.com/user-attachments/assets/fd430dd1-7673-4fe9-95f4-b8fab3c4b976" />
<img width="940" height="534" alt="image" src="https://github.com/user-attachments/assets/8846335d-cbd2-4ee5-8fd7-1cf964b51092" />
<img width="940" height="534" alt="image" src="https://github.com/user-attachments/assets/48f4dd36-6e33-4149-ac42-c5bf7b2378a2" />


### Task 3: Test IAM User Permissions
- Logged in using IAM sign-in URL  
- Verified S3 access for user-1  
- Verified EC2 read-only access for user-2  
- Verified EC2 administrative access for user-3  

<img width="940" height="536" alt="image" src="https://github.com/user-attachments/assets/a1a1b9fa-8b5d-42d2-977a-6fda086f9cf5" />
<img width="940" height="536" alt="image" src="https://github.com/user-attachments/assets/419a3d0a-1300-4aa0-a3d9-63acc7d99dda" />
<img width="940" height="538" alt="image" src="https://github.com/user-attachments/assets/57b8b107-2af2-450b-b10c-74f13c735a8e" />




## Workflow
1. Accessed IAM console and reviewed users and groups.  
2. Inspected policy permissions attached to groups.  
3. Assigned users to groups based on their roles.  
4. Logged in as each IAM user using the sign-in URL.  
5. Validated permissions by accessing AWS services.  


## Learning Outcomes
- Understood the role of IAM in AWS security.  
- Learned how IAM users, groups, and policies interact.  
- Gained practical experience implementing role-based access control.  
- Verified permission enforcement through real-time service testing.  

<img width="940" height="538" alt="image" src="https://github.com/user-attachments/assets/8fa4100e-9113-4ca8-995b-b5bc10698f84" />


## Conclusion
This lab provided hands-on experience with AWS IAM by demonstrating how organizations manage secure access to cloud resources. Assigning users to groups with predefined policies simplified permission management and ensured role-based access control across AWS services.


## Author
**Name:**    Gokul S (212224230075)
**Course:** Introduction to Cloud Computing  

