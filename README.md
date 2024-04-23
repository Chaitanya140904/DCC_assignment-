# DCC_assignment

Setting Up the Electoral Bonds Website Locally
This repository is created as a part of the course ES 113 - Data Centric Computing at the Indian Institute of Technology, Gandhinagar, under Professor Mayank Singh. It contains data for a website designed to analyze electoral bonds purchase and redemption details.

Setup Instructions
Download the Repository:
Download the repository as a ZIP file.
Import Data into MySQL:
Using MySQL Workbench or any other MySQL client, import the data from the dump_data.sql dump file provided in the repository.
Create MySQL User:
Execute the following SQL code in MySQL Workbench to create a new user and grant privileges:
sql
Copy code
CREATE USER 'testing@' @'localhost' IDENTIFIED BY 'password';
GRANT ALL PRIVILEGES ON *.* TO 'testing@'@'localhost' WITH GRANT OPTION;
Configure my_flask.py:
Open the my_flask.py file.
If you have modified the username or password in step 3, update the MYSQL_USER and MYSQL_PASSWORD variables accordingly:
python
Copy code
app.config['MYSQL_USER'] = 'testing@'
app.config['MYSQL_PASSWORD'] = 'password'
Run the Flask App:
Navigate to the directory containing my_flask.py in the terminal.
Run the Python file:
python my_flask.py
Access the Website:
Open a web browser and navigate to http://127.0.0.1.
The website should load and be accessible locally.



DCC Assignment 
 1e1 
  
 
 
 
 
 
1e2 
 
   
1e3
   
  
 	  
 
1e4
   
 
1e5
   
 
 	  
 





