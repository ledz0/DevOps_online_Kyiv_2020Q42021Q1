# Module 3 Database Administration.

## TASK 3.1

### PART 1

1. MySQL server successfully installed on Ubuntu 20.04. Database was created and filled :</br></br>
   ![1](./screenshots/1.png)</br></br>
   ![1](./screenshots/2.png)</br>
   ![1](./screenshots/3.png)</br>

2. Operators:
   WHERE</br>
   ![1](./screenshots/4.png)</br></br>
   ORDER BY</br>
   ![1](./screenshots/5.png)</br></br>
   GROUP BY</br>
   ![1](./screenshots/6.png)</br></br>

3. SQL queries that I used :</br></br>
   **DDL - create, alter, drop :**</br>
   ![1](./screenshots/7.png)</br></br>
   ![1](./screenshots/8.png)</br></br>
   ![1](./screenshots/9.png)</br></br>

   **DML - select, insert, update :**</br>
   ![1](./screenshots/4.png)</br></br>
   ![1](./screenshots/10.png)</br></br>
   ![1](./screenshots/11.png)</br></br>

   **DCL - grant, revoke :**</br>
   ![1](./screenshots/12.png)</br></br>

4. Created new user and connected to the database with all privileges.</br>
   ![1](./screenshots/13.png)</br></br>

### PART 2

5. Backup of database is done using the next CL and Database is restored using the next CL :</br> -_sudo mysqldump careers > backup_career_db.sql_</br></br> -_sudo mysql new_sunroof_DB < backup_sunroof_DB.sql_</br>
   ![1](./screenshots/14.png)</br>
   ![1](./screenshots/15.png)</br>
   ![1](./screenshots/16.png)</br>

6. Table and database were deleted using the next CL :</br>
   - _drop table skill;_
   - _drop database careers;_
