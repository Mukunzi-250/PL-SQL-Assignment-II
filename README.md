Assignment II: Database Creation, Deletion & OEM

NAME: Mukunzi eduine

ID: 29275

Date: 10/07/2025


Q1. How to create new pluggable database
CREATE PLUGGABLE DATABASE ed_pdb_29275 ADMIN USER eduine_plsqlauca_29275 IDENTIFIED BY "eduine123@" FILE_NAME_CONVERT = ( 'C:\ORACLE21C\ORCL\PDBSEED', 'C:\ORACLE21C\ORCL\ED_PDB_29275' );

 <img width="1006" height="257" alt="image" src="https://github.com/user-attachments/assets/a7b5ed8b-a3d9-43b9-92ea-900e630253f8" />

Q2. Create PDB with format ed_to_delete_pdb_29275
CREATE PLUGGABLE DATABASE ed_to_delete_pdb_29275 ADMIN USER ed_admin2 IDENTIFIED BY "eduine123@" FILE_NAME_CONVERT = ( 'C:\ORACLE21C\ORCL\PDBSEED', 'C:\ORACLE21C\ORCL\ED_TO_DELETE_PDB_29275' );

 <img width="1026" height="267" alt="image" src="https://github.com/user-attachments/assets/cb9e6990-cb79-4827-a2e8-06a0281664cf" />

Q3. Deleting PDB with format ed_to_delete_pdb_29275
DROP PLUGGABLE DATABASE ed_to_delete_pdb_29275 INCLUDING DATAFILES;

<img width="1032" height="160" alt="image" src="https://github.com/user-attachments/assets/1ff3f90f-1988-41b2-9121-bc82c5f65bf0" />


Q4. Oracle Enterprise Manager (OEM) 
1.Open and configure Oracle Enterprise Manager.

<img width="975" height="479" alt="image" src="https://github.com/user-attachments/assets/9885ad88-614b-4270-b241-1cc6e8bed903" />

 

Q4. Oracle Enterprise Manager (OEM) 
1.Open and configure Oracle Enterprise Manager.
 

