## User Management in AWS IAM

## Project Overview

This project demonstrates secure user management using AWS Identity and Access Management (IAM).

The project creates different IAM users and groups and assigns permissions based on their roles. Multi-Factor Authentication (MFA) is also enabled to improve account security.

## Objectives

- To create and manage IAM users.
- To organize users into IAM groups.
- To assign permissions using IAM policies.
- To implement authentication and authorization.
- To enable Multi-Factor Authentication (MFA).
- To follow the principle of least privilege.

## IAM Users and Permissions

User| Group| Permission
Project-Admin| Project-Admin-Group| AdministratorAccess
Project-Developer| Project-Developer-Group| AmazonS3FullAccess
Project-Viewer| Project-Viewer-Group| ReadOnlyAccess

## Technologies Used

- Amazon Web Services (AWS)
- AWS Identity and Access Management (IAM)
- IAM Users
- IAM Groups
- IAM Policies
- Multi-Factor Authentication (MFA)

## Key Concepts

Authentication

Authentication verifies the identity of an IAM user during login.

Authorization

Authorization determines what actions an authenticated user is allowed to perform.

Role-Based Access

Different users receive different permissions according to their project roles.

Multi-Factor Authentication

MFA provides an additional security layer during authentication.

Principle of Least Privilege

Users are given only the permissions required for their assigned role.

## Implementation

1. Created IAM users for Admin, Developer, and Viewer.
2. Created separate IAM groups for each user role.
3. Attached appropriate IAM policies to the groups.
4. Added users to their respective groups.
5. Enabled MFA for the IAM users.
6. Tested user authentication and permissions.
7. Verified that different users have different levels of access.

## Expected Result

The project successfully demonstrates secure AWS user management.

- Project-Admin has administrative access.
- Project-Developer has S3-related access.
- Project-Viewer has read-only access.
- MFA provides additional authentication security.
- Group-based permissions help implement controlled access and least privilege.

## Conclusion

This project demonstrates how AWS IAM can be used to securely manage users, groups, permissions, authentication, authorization, and MFA. Different access levels are provided according to user roles, improving security and reducing unauthorized access.

## Project Team
-Chandrakumar S - 44110126
-Dhaanya Roopa A B -44110149

## Project: User Management in AWS IAM

Platform: Amazon Web Services (AWS)
