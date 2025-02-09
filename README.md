Cloud Security with AWS IAM

Objective
This project demonstrates how to use AWS IAM (Identity and Access Management) to secure AWS resources by managing user access, roles, policies, and permissions. The focus is on implementing the principle of least privilege while ensuring secure and efficient resource management.

Steps
1. Create IAM Users and Groups
   - Created IAM user accounts for team members.
   - Assigned users to groups for easier permission management.
2. Define IAM Policies
   - Used JSON policies to grant permissions only to necessary resources.
   - Restricted actions on production EC2 instances while allowing actions on development instances.
3. Use Tags for Resource Organization
   - Tagged EC2 instances with `Environment=Production` and `Environment=Development`.
   - Created IAM policies to enforce resource-based access control.
4. Set Up an Account Alias
   - Created a custom AWS account alias for easier login management.
5. Test IAM Policies
   - Verified access control by attempting to stop EC2 instances.
   - Confirmed that production instances were protected while development instances were accessible.

Things Learned
- How to create and manage IAM users and groups efficiently.
- How to define IAM policies using JSON to enforce fine-grained permissions.
- How to use resource tags to simplify access management and organization.
- How to implement and test least privilege access to secure AWS environments.


Arjun Singh  
NextWork Student  
[NextWork.org](https://nextwork.org)
