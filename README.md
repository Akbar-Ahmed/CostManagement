# CostManagement
Automatically Scheduling Multiple EC2 Instances.

Steps to run the project:

1-Create multiple EC2 instance.
2-Create a policy 
3-Attach roles to that policy ( for use case select lambda)
4-Create  lambda functions both starting and stopping the EC2 instances. 
(Note : I have attached the code for the lambda function in the repository)
5- For Automation,go to Cloudwatch 
6-Create rule by providing crom expression


The EC2 are now scheduled according to the requirement.


