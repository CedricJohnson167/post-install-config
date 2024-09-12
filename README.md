# post-install-config
Admin/Analyst Login Page:
http://localhost/osTicket/scp/login.php 
login with adminuser and password1 that was set before
<img width="1225" alt="Screenshot 2024-09-11 at 3 42 52 PM" src="https://github.com/user-attachments/assets/769bdf36-a0c7-48f9-8530-1fce70bdefe8">





End Users osTicket URL:
http://localhost/osTicket 
<img width="1225" alt="Screenshot 2024-09-11 at 3 42 35 PM" src="https://github.com/user-attachments/assets/a099eb61-46b6-49f7-94a9-84aabbd908ff">




Acknowledge Agent Panel vs Admin Panel
<img width="1225" alt="Screenshot 2024-09-11 at 4 06 05 PM" src="https://github.com/user-attachments/assets/3bd22d29-9a68-47d1-968a-6fc90a69cf04">
<img width="1225" alt="Screenshot 2024-09-11 at 4 07 06 PM" src="https://github.com/user-attachments/assets/9ec75d5a-fe82-4b71-9224-db32d1da5a9e">



Configure Roles (for grouping permissions)
Admin Panel -> Agents -> Roles
Supreme Admin
<img width="1225" alt="Screenshot 2024-09-11 at 4 08 36 PM" src="https://github.com/user-attachments/assets/2d6c9ff5-c235-42dc-a585-ced654d35974">
<img width="1225" alt="Screenshot 2024-09-11 at 4 09 23 PM" src="https://github.com/user-attachments/assets/898e10c4-33f0-4dad-a3d9-f229a4750039">
<img width="1225" alt="Screenshot 2024-09-11 at 4 09 41 PM" src="https://github.com/user-attachments/assets/28d613d7-ba64-41c8-ad94-d75e6a60e1fb">





Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)
Admin Panel -> Agents -> Departments
SysAdmins
<img width="1225" alt="Screenshot 2024-09-11 at 4 11 49 PM" src="https://github.com/user-attachments/assets/e7eabe8d-ce93-4f1a-940a-71d41570326a">
<img width="1225" alt="Screenshot 2024-09-11 at 4 12 04 PM" src="https://github.com/user-attachments/assets/0e73ed52-4451-4bcb-8bef-064b34a67a08">
<img width="1225" alt="Screenshot 2024-09-11 at 4 12 24 PM" src="https://github.com/user-attachments/assets/104f5161-c8e5-4787-9300-01bcbeb669f8">
<img width="1225" alt="Screenshot 2024-09-11 at 4 12 33 PM" src="https://github.com/user-attachments/assets/5f986ddb-81d1-4169-880a-340df2556128">





Configure Teams
Admin Panel -> Agents -> Teams (Pull Agents from different Departments)
Online Banking
<img width="1225" alt="Screenshot 2024-09-11 at 4 13 03 PM" src="https://github.com/user-attachments/assets/2b46c4ce-4b1e-4d3e-938f-902dd0b09e6d">
<img width="1225" alt="Screenshot 2024-09-11 at 4 13 27 PM" src="https://github.com/user-attachments/assets/1ddfa2f8-9752-437d-bb98-bc5a83a98031">
<img width="1225" alt="Screenshot 2024-09-11 at 4 13 43 PM" src="https://github.com/user-attachments/assets/9288a00b-b200-4298-b802-bc0f891a345d">





Allow anyone to create tickets
Admin Panel -> Settings -> User Settings (UNCHECK: unregistered users can create tickets)
Registration Required: Require registration and login to create tickets 
<img width="1225" alt="Screenshot 2024-09-11 at 4 13 55 PM" src="https://github.com/user-attachments/assets/98ce26de-dd54-4892-b505-dbec7add2274">
<img width="1225" alt="Screenshot 2024-09-11 at 4 14 06 PM" src="https://github.com/user-attachments/assets/cde83484-029d-4848-967b-a301aa6aa473">





Configure Agents (workers)
Admin Panel -> Agents -> Add New
Jane (Dept: SysAdmins)
John (Dept: Support)
<img width="1225" alt="Screenshot 2024-09-11 at 4 14 41 PM" src="https://github.com/user-attachments/assets/15444a1b-61ea-4b73-a4cb-8314a4575da9">
<img width="1225" alt="Screenshot 2024-09-11 at 4 15 26 PM" src="https://github.com/user-attachments/assets/a80c91ac-a073-4d6e-a746-ce0fd0944e42">
<img width="1225" alt="Screenshot 2024-09-11 at 4 16 24 PM" src="https://github.com/user-attachments/assets/bdf5766c-a423-4cf3-8156-dcc19b9201b8">
<img width="1225" alt="Screenshot 2024-09-11 at 4 16 46 PM" src="https://github.com/user-attachments/assets/6375b446-6eda-41a3-b674-1e4dd2d148ab">
<img width="1225" alt="Screenshot 2024-09-11 at 4 16 53 PM" src="https://github.com/user-attachments/assets/d0fc437e-7697-4948-a9d3-ff14bd9e2ced">



Configure Users (customers)
Agent Panel -> Users -> Add New
Karen
Ken
<img width="1225" alt="Screenshot 2024-09-11 at 4 17 17 PM" src="https://github.com/user-attachments/assets/49ad9c7e-a607-4746-979d-efd7ebf564ac">
<img width="1225" alt="Screenshot 2024-09-11 at 4 17 31 PM" src="https://github.com/user-attachments/assets/7b96cbaa-0688-416f-8629-6543abb36b17">
<img width="1225" alt="Screenshot 2024-09-11 at 4 17 43 PM" src="https://github.com/user-attachments/assets/68c8e787-abe6-4e14-a26f-27a3f9492ca0">




Configure SLA
Admin Panel -> Manage -> SLA
Sev-A (Grace Period: 1 hour, Schedule: 24/7)
Sev-B (Grace Period: 4 hours, Schedule: 24/7)
Sev-C (Grace Period: 8 hours, Business Hours)
<img width="1225" alt="Screenshot 2024-09-11 at 4 18 12 PM" src="https://github.com/user-attachments/assets/490d62d7-a58e-4905-a5b6-70ac5e009b0b">
<img width="1225" alt="Screenshot 2024-09-11 at 4 18 31 PM" src="https://github.com/user-attachments/assets/951ff787-d8c7-4cb3-88d9-dd3f74b04368">
<img width="1225" alt="Screenshot 2024-09-11 at 4 18 53 PM" src="https://github.com/user-attachments/assets/3dc84d76-7525-412b-826b-2eb805e0f5dd">
<img width="1225" alt="Screenshot 2024-09-11 at 4 19 04 PM" src="https://github.com/user-attachments/assets/4c1d083f-10d1-4166-be57-85aba0a8727a">




Configure Help Topics (For when users create a ticket)
Admin Panel -> Manage -> Help Topics
Business Critical Outage
Personal Computer Issues
Equipment Request
Password Reset
Other
<img width="1225" alt="Screenshot 2024-09-11 at 4 20 08 PM" src="https://github.com/user-attachments/assets/e6845128-efd2-4b0f-a8d1-284d22e07336">
<img width="1225" alt="Screenshot 2024-09-11 at 4 20 36 PM" src="https://github.com/user-attachments/assets/329a7aed-8ef0-430a-9312-7d8a39b4d80e">
<img width="1225" alt="Screenshot 2024-09-11 at 4 20 57 PM" src="https://github.com/user-attachments/assets/3201decf-f4c6-4c52-be37-5f95a243c771">
<img width="1225" alt="Screenshot 2024-09-11 at 4 21 05 PM" src="https://github.com/user-attachments/assets/3341b993-a8b0-4dc9-b1c9-c3057377d10f">


