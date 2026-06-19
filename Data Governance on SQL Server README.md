__Create multiple Login Users, Database Users to apply Role based Security. Apply Dynamic Data Masking__

Step 1: Create 4 Login Users.

<img width="558" height="105" alt="image" src="https://github.com/user-attachments/assets/f9c2d8fa-aa82-4ed9-bfad-ce677216956e" />


Step 2: Select the Database on which Users must be created. Create the Users on the 'ClinicalTrials Database to map the same login credentials from previous step. Apply Role-Based Permissions (RBAC) on ClinicalTrials Database only. 
<img width="1257" height="635" alt="image" src="https://github.com/user-attachments/assets/68bc4cd6-3d38-4f00-9d83-4f307a26965b" />


Step 3: Establish connections with Server Login Credentials from Step 1. Ensure the connections are established for 4 login users.
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/0e06b27e-42ba-45a5-80ae-fc85f906ec95" />

Step 4: Perform Column masking
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b5601957-c129-41c8-8dae-d745252efd74" />

__Validate the Policies on Power BI with Dynamic Data Masking and Role Level Security__

Step 1. Establish SQL Server Connection on Power BI and Login as Business Analyst User.
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e02397af-bf68-41c9-8768-cbdbad6e6a7e" />

Step 2. Total 5 tables and 1 view would be visible from the login user Business Analyst on Power BI.
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/f702bc53-6eec-42aa-b489-3a2b63f6b7a9" />

Step 3: Establish connection with SQL Server as Data Analyst User.
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/163cdd79-e933-410e-a229-19d7f05914c9" />

Step 4: Total 6 tables will be dsiplayed for Data Analyst along with Data Masking policy.
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/14be3b38-43ca-4491-8d06-d3d278832e21" />

Step 5: Select Policy was denied for Data Analyst on 'Lab Result' table followed by Role based access restriction.
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/a5fac2cc-226b-4f4e-9562-f78d5bc0a7ac" />
















