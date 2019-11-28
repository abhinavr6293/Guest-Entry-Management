# Guest-Entry-Management

An Employee and guest entry management software where both employee and visitor can enter their check in and check out time in the log book and do a lot more with it. It also has a portal for both employees and visitor.

Short Description
This is a software which can efficiently manage your Entry book. From performing tasks like viewing all the logs. It has two portals on the homepage, one for Employee and the other for Visitor. Both Employee and Visitor can -

Check In
Check Out
Enter required details such as EmpID, Dept , visting person, etc.
Search for a specific log
You can either check In as an Employee if you haven't done that yet or else just Login like any other portal, same applies to the Visitor portal. Once you register yourself you will be added to the serveside database from where your details will be fetched at the time of login.

NOTE:
This project is subject to change by the developer and is still in development

Things you need before getting started --
Install these packages if you don't have them already in your system

tkinter - pip install tkinter
Pillow - pip install pillow
PyMySql - pip install pymysql
Create a database with any name and give your database name and password to-

main.py - line 21 and 22
AddBooks.py - line 56 and 57
DeleteBook.py - line 16 and 17
IssueBook.py - line 16 and 17
SearchBook.py - line 16 and 17
ViewBook.py - line 16 and 17
Create an Employee table with any name and add the following attributes to it - empid(PK),name,Key,dept,doj,checkIn (Everything should be varchar) (Please keep the names of the attributes as given here)

Syntax - create table <tablename> (empid varchar(20) primary key,name varchar(30),password varchar(30),dept varchar(30),doj varchar(30),sal varchar(30));

Then go ahead and paste you employee table name to -

main.py - line 25
IssueBook.py - line 26

Clone this repository
Double click on main.py
