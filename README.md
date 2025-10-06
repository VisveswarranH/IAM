EX - 6 Implementation Of Identity Management (Amazon IAM) For Your Team
Name: Visveswarran Harikrishnan
Reg No: 212224110063
Aim
To implement identity and access management (IAM) in AWS to securely control access to resources by creating and managing IAM users, groups, roles, and policies for team collaboration.

Algorithm
Sign in to the AWS Management Console.
Navigate to the IAM service.
Create IAM groups with defined policies (e.g., Admin, Developer).
Create IAM users and assign them to appropriate groups.
Create IAM roles if cross-account or service-based access is needed.
Attach permissions using managed or custom policies.
Enable MFA (Multi-Factor Authentication) for users.
Monitor access using IAM Access Analyzer and CloudTrail.
Procedure
1. Access IAM
Go to AWS Console → Services → IAM.
2. Create IAM Groups
Click Groups → Create New Group.
Name the group (e.g., Admins, Developers).
Attach predefined or custom policies (e.g., AmazonEC2FullAccess).
3. Create IAM Users
Click Users → Add Users.
Enter usernames and choose Programmatic access and/or AWS Management Console access.
Assign users to the appropriate group.
4. Create IAM Roles (if needed)
Go to Roles → Create Role.
Select use case (AWS service, another AWS account).
Attach necessary permissions.
5. Apply Policies
Use AWS managed policies or create custom JSON-based policies.
Assign them to users, groups, or roles.
6. Enable MFA
For each user, go to Security credentials.
Click Manage MFA → Choose Virtual MFA device (e.g., Google Authenticator).
7. Monitor IAM Usage
Use IAM Access Analyzer to detect unused permissions.
Use CloudTrail for auditing user activity.
Outcome
IAM users, groups, and roles were successfully created with appropriate permissions and MFA configured to ensure secure identity management for the team.
Result
Successfully implemented identity and access management using Amazon IAM for secure team collaboration and controlled access to AWS resources.

About
No description, website, or topics provided.
Resources
 Readme
 Activity
Stars
 0 stars
Watchers
 0 watching
Forks
 0 forks
Report repository
Releases
No releases published
Packages
No packages published
