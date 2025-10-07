 Assignment II: Database Creation, Deletion & OEM
NAME: Mukunzi eduine
ID: 29275
Date: 10/07/2025

Q1. How to create new pluggable database
CREATE PLUGGABLE DATABASE ed_pdb_29275 ADMIN USER eduine_plsqlauca_29275 IDENTIFIED BY "eduine123@" FILE_NAME_CONVERT = ( 'C:\ORACLE21C\ORCL\PDBSEED', 'C:\ORACLE21C\ORCL\ED_PDB_29275' );
 
Q2. Create PDB with format ed_to_delete_pdb_29275
CREATE PLUGGABLE DATABASE ed_to_delete_pdb_29275 ADMIN USER ed_admin2 IDENTIFIED BY "eduine123@" FILE_NAME_CONVERT = ( 'C:\ORACLE21C\ORCL\PDBSEED', 'C:\ORACLE21C\ORCL\ED_TO_DELETE_PDB_29275' );
 
Q3. Deleting PDB with format ed_to_delete_pdb_29275
DROP PLUGGABLE DATABASE ed_to_delete_pdb_29275 INCLUDING DATAFILES;

 

Q4. Oracle Enterprise Manager (OEM) 
1.Open and configure Oracle Enterprise Manager.
 

