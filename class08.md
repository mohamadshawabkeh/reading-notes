# Access Control (ACL)

## 5 steps to RBAC
1. What is Role Based Access Control (RBAC) and why do we care?
   - RBAC is a security model that controls resource access based on assigned roles. We care about RBAC because it ensures the principle of least privilege, granting access only to necessary resources for each user's role.

2. Describe a Role/Permission hierarchy that you might implement using RBAC.
   - In an RBAC system, you can have roles such as "Admin," "Manager," and "Employee." Admin has the highest permissions, followed by Manager, and then Employee with limited permissions.

3. What approach might you take to implement RBAC?
   - To implement RBAC, you can follow these steps:
     1. Identify roles and their associated permissions.
     2. Map users to roles based on their responsibilities.
     3. Define access rules that specify which roles can access which resources.
     4. Regularly review and update access privileges to ensure they align with changing requirements.

## wiki - RBAC
1. If Authentication is "you are who you say you are," what is Authorization?
   - Authorization determines what actions a user with a specific role or permission is allowed to perform on a resource after successful authentication.

2. Name three primary rules defined for RBAC.
   - The three primary rules defined for RBAC are:
     1. Role assignment: Users are assigned specific roles that define their access rights.
     2. Role authorization: Roles are granted or denied access to resources based on permissions.
     3. User permissions: Users can perform actions based on their assigned roles and associated permissions.

3. Describe RBAC to a non-technical friend.
   - RBAC is a system that ensures the right people have the right access to resources. It uses roles to define what actions different users can perform, making sure that everyone has the appropriate level of access and reducing security risks.

## RBAC tutorial
1. What are access rights associated with? The User or The Role? Explain.
   - Access rights in RBAC are associated with the Role. Users are assigned roles, and each role has specific access rights to resources. Users inherit access rights from the roles they are assigned.

2. Access Rights, or Authorization, is activated after a user successfully does what?
   - Authorization, or access rights, is activated after a user successfully authenticates their identity by providing valid credentials, such as a username and password.

3. Explain how RBAC might benefit a business.
   - RBAC can benefit a business in several ways:
     - Improved security by limiting access to resources based on roles and permissions.
     - Simplified access management through centralized control and administration of roles and permissions.
     - Reduced risk of errors or unauthorized access by granting access only to necessary resources.
     - Ensured compliance with regulations and policies by enforcing access control based on predefined rules.




 ### return to [Main Read Me File](./README.md)