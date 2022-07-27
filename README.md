# CostManagement
Automatically Scheduling Multiple EC2 Instances.

Steps to run the project:

1-Create multiple EC2 instance.
![Screenshot (898)](https://user-images.githubusercontent.com/70852077/181308161-d0e11125-86c1-4fd6-8d82-dbd08f475bff.png)


2-Create a policy 

![Screenshot (893)](https://user-images.githubusercontent.com/70852077/181307192-29a9d814-37d9-40b0-8bfe-aeba09425319.png)


3-Attach roles to that policy ( for use case select lambda)

4-Create  lambda functions both starting and stopping the EC2 instances. 
(Note : I have attached the code for the lambda function in the repository)

5- For Automation,go to Cloudwatch 

6-Create rule by providing crom expression

![Screenshot (901)](https://user-images.githubusercontent.com/70852077/181307811-b0979224-f062-46f8-8c9d-9c6bed22d7a5.png)



The EC2 are now scheduled according to the requirement.


