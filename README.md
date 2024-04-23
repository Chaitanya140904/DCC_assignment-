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
 1e1   Bond Number -1118
  
 <img width="1440" alt="Screenshot 2024-04-23 at 5 34 04 PM" src="https://github.com/Chaitanya140904/DCC_assignment-/assets/154114491/f90ab721-3a90-4c04-8f1c-362596a830e0">
 
 
 
 
1e2 Company Name – SHANKARNARAYANA CONSTRUCTIONS LIMITED

<img width="1440" alt="Screenshot 2024-04-23 at 5 35 33 PM" src="https://github.com/Chaitanya140904/DCC_assignment-/assets/154114491/0dbbc6e6-6d90-46d0-afda-2a703c5322be">

1e3 PARTY NAME – BHARTIYA JANATA PARTY
   
<img width="1440" alt="Screenshot 2024-04-23 at 5 37 59 PM" src="https://github.com/Chaitanya140904/DCC_assignment-/assets/154114491/14c0360a-812d-424c-9a9d-c90a4b67399a">
 	  
 
1e4 PARTY NAME - – BHARTIYA JANATA PARTY
 <img width="1440" alt="Screenshot 2024-04-23 at 5 38 09 PM" src="https://github.com/Chaitanya140904/DCC_assignment-/assets/154114491/4fdc1adf-3ce0-4c13-949b-cff616c58c36">  
 
1e5 nameofthecompany-AJITKUMARJAIN
   
<img width="1440" alt="Screenshot 2024-04-23 at 5 39 14 PM" src="https://github.com/Chaitanya140904/DCC_assignment-/assets/154114491/da3de66a-363a-45a4-9fcf-a6c86af7c174"> 
 	  
 





