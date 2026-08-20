1. Introduction
I want to introduce my topic as A Hospital Management System is used to manage important information about patients, doctors, nurses, medicines, appointments, medical records and billing. Since this system contains sensitive patient information, it is important to control who can access different parts of system.
For this purpose, I have considered Role – Based Access Control (RBAC). RBAC allows users to access the system according to their assigned roles. Different hospital employees have different responsibilities, so they should not have the same level of access.
For example, a doctor needs access to patient medical records, while a receptionist mainly needs access to appointments and patient registration. Similarly, an administration needs higher – level access to manage hospital users and system information.
2. What is RBAC?
RBAC stands for Role – Based Access Control. It is a security method in which permissions are given to users on their roles.
The basic working of RBAC is:
User

Role

Permission
                                                                  
Hospital Resource
For example:
Doctor

Doctor Role

Update Medical Records

Patient Records
If a user has the required permission, the system allows access. If the user does not have the required permission, the system denies access.
Users are then assigned to the appropriate role. This makes the system easier to manage and improves security.
3. Roles in the Hospital Management System
In my implementation, I considered four main roles: 
•	Administrator
•	Doctor
•	Nurse
•	Receptionist
4. Working of the RBAC System:
The working of the system starts with the login process. Each employee enters their username and password. The system checks the login details and identifies the user’s role.




For Example:
Doctor Login

Doctor Role

View Reports

Doctor Dashboard
Conclusion:
In this project, I implemented the concept of Role – Based Access Control for a Hospital Management System. The system provides different permissions to administrators, doctors, nurses and receptionists based on their responsibilities.
The main purpose of RBAC is to make sure that every user can access only the information and functions required for their work.

