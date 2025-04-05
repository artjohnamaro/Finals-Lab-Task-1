# Finals Lab Task 1: MySQL Basics
- This portfolio demonstrates foundational MySQL skills through the development of a multi-level company database. It covers key tasks such as writing SQL queries, designing table structures, and creating an ER diagram or relational schema. Additionally, it includes SQL scripts for the database and table structures to illustrate the database's design and implementation.

## Step By Step Process
✅ **Task 1: Create employees Table**
- Define employee_id as auto-incremented primary key.

- Add employee_name as VARCHAR(255) and NOT NULL.

- Add manager_id as a foreign key referencing employee_id in the same table.

✅ **Task 2: Create departments Table**
- Define department_id as auto-incremented primary key.

- Add department_name as VARCHAR(255) and NOT NULL.

✅ **Task 3: Create employee_departments Table**
- Add employee_id referencing employees.employee_id.

- Add department_id referencing departments.department_id.

- Set a composite primary key on both.

✅ **Task 4: Create employee_projects Table**
- Add employee_id referencing employees.employee_id.

- Add project_name as VARCHAR(255) and NOT NULL.

✅ **Task 5: Create managers Table**
- Define manager_id as auto-incremented primary key.

- Add employee_id referencing employees.employee_id.

## QUERY STATEMENTS
1. Employees Table
- ![Image](https://github.com/user-attachments/assets/1aed1970-e068-45ca-8f0a-adda58560475)
2. Department Table
- ![Image](https://github.com/user-attachments/assets/cc07ab27-da9a-4ea1-85ab-87ff6385b587)
3. Employees Department Table
- ![Image](https://github.com/user-attachments/assets/f813e600-2b58-4aba-a7ca-4f2c36e4bf06) 
4. Employee Projects Table
- ![Image](https://github.com/user-attachments/assets/9da77510-ef70-4288-8f1b-940f7b9f33df) 
5. Managers Table
- ![Image](https://github.com/user-attachments/assets/c4ef296b-aabe-46a6-8543-daa5cf60408e)

## TABLE STRUCTURE
1. Employees Table
- ![Image](https://github.com/user-attachments/assets/305ae660-2f15-40f8-8cc7-4b528a49856c)
2. Department Table
- ![Image](https://github.com/user-attachments/assets/734a0b63-7efa-414a-a602-8b7e412f2dc7) 
3. Employees Department Table
- ![Image](https://github.com/user-attachments/assets/660e3875-c19f-4292-9931-7cfbb17637ef) 
4. Employee Projects Table
- ![Image](https://github.com/user-attachments/assets/51a0802b-bc7c-4045-b489-e27221e60bad) 
5. Managers Table
- ![Image](https://github.com/user-attachments/assets/507513ed-27b4-49bb-9086-6cd18c3da507)

## EER DIAGRAM
![Image](https://github.com/user-attachments/assets/9495e871-0ace-4e1c-8c44-93bdd3685134)

