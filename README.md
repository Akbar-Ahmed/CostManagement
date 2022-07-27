# CostManagement
Automatically Scheduling Multiple EC2 Instances.

Steps to run the project:

1-Create multiple EC2 instance.

2-Create a policy 

![Screenshot (893)](https://user-images.githubusercontent.com/70852077/181307192-29a9d814-37d9-40b0-8bfe-aeba09425319.png)


3-Attach roles to that policy ( for use case select lambda)
4-Create  lambda functions both starting and stopping the EC2 instances. 
(Note : I have attached the code for the lambda function in the repository)
5- For Automation,go to Cloudwatch 
6-Create rule by providing crom expression


The EC2 are now scheduled according to the requirement.


