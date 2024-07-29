# sql-challenger
Im a newly hired data engineer with Pewlett Hackard! Don't worry, its fictional! 
My task as a newly hired employee is to complete a research project about previously employeed people during the 1980s and 1990s.
I will use the 6 CSV files supplied in order to complete this. 
I will:
-Design a table to hold the data from the CSV files
- Import the CSV files into a SQL database
- Answer questions about the data

All of those actions will showcase my ability to perform:
-Data modeling
-Data engineering
-Data analysis

SOFTWARE NEEDED
This project used pgADMIN 4

DataSource
The files needed for the project was provided by the course. The data was given as a CSV file. The files were to be imported into pgAdmin into the tables created.

Code Explanation
The following codes used created the tables the csv files will be imported to. Firstly, while creating the tables, The values had to be given such as: Primary Key (PK), Foreign Key (FK), VARCHAR< INT, Date, which explains data type of the information in the "cell". A quick explanation: The Primary Key is the attribute that does NOT change throughout its existence. Its a value that will allow easy identification of a person, place or thing becuase the value is unique to that one piece of data. The Foreign Key is when the primary key is used on a different table but its the connecting piece between the tables. 
![Table_Setup_pt1](https://github.com/user-attachments/assets/7d365ee8-3675-4bee-9e90-7211d97348f3)
![Table_Setup_pt2](https://github.com/user-attachments/assets/f2ad5d81-c2ab-441d-8a85-17fcdaa7d7be)

After creating the tables and assigning the data type values, the CSV files needed to be imported. It was imperative the imports were done in the order the tables were created. If not, an error would occur.

Results and Evaluation:
Each question will have a picture with the answer:

-List the employee number, last name, first name, sex, and salary of each employee
  ![1st_Question](https://github.com/user-attachments/assets/752c1718-d453-488b-803f-ddc2b433df6b)

-List the first name, last name, and hire date for the employees who were hired in 1986 
  ![2nd_Question](https://github.com/user-attachments/assets/f9119810-5345-440a-97f8-0a392b5e1544)

-List the manager of each department along with their department number, department name, employee number, last name, and first name 
  ![3rd_Question](https://github.com/user-attachments/assets/eb3d77dd-2d9e-4479-99ba-3f2b89df5f97)

-List the department number for each employee along with that employee’s employee number, last name, first name, and department name 
  ![4th_Question](https://github.com/user-attachments/assets/32e5788d-20b7-4f61-b774-74703ab63f84)

-List first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B 
  ![5th_Question](https://github.com/user-attachments/assets/685c8913-f190-4258-8235-0a9603cdd177)

-List each employee in the Sales department, including their employee number, last name, and first name 
  ![6th_Question](https://github.com/user-attachments/assets/f7700a43-116a-4ba4-9857-42116b6fe7c1)

-List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name 
  ![7th_Question](https://github.com/user-attachments/assets/5735d254-b376-498b-9952-66933934786c)

-List the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name)
  ![8th_Question](https://github.com/user-attachments/assets/45e7e8d9-15dd-495f-a1ca-f9cfadfe8ab6)

Please enjoy...
