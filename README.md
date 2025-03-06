**Library Management System**

**Project Overview**

A complete database solution created to effectively manage a library's operations is the Library Management System. SQL is used for data visualization, reporting, and analysis in this project, while SQL is used for database administration. Effective tracking of books, patrons, staff, book issuing, returns, and library branches is made possible by the system. By automating record-keeping, enhancing accessibility, and offering deep analytics through SQL queries and Excel-based reporting, it guarantees seamless operations.

**Project Objectives**

Create a structured database to effectively store and handle library-related data.
To retrieve, update, and analyze data for efficient decision-making, use SQL queries.
Excel can be used for reporting, visualization, and improved data understanding.
Establish a user-friendly system to monitor books, clients, staff, book transactions, and branches.
Automated record management can increase library operations' accuracy and efficiency.

**Database Setup & Schema**

Setting up a SQL database called "Library" to hold structured data is the first step in the project. There are several interconnected tables in the database:

**1.Book Management**

keeps track of the library's available books.

keeps book information, such as:

Title
Category (e.g., Fiction, Science, History, etc.)
Rental price
Availability status
Author and Publisher

**2. Customer Management**

keeps track of the patrons who use the library.

keeps client data in storage, such as

Name
Address
Registration date
Issuance history

**3. Employee Management**

keeps track of library staff members' personal information.

Maintains employee records, including:

Name
Position (Librarian, Assistant, etc.)
Salary
Branch Assignment

**4. Book Issuance & Returns**

keeps track of all book transactions, including returns and issuance.
maintains book availability by making sure returns are made on schedule.
keeps track of issued books and their corresponding clients.

**5. Branch Management**

keeps track of information about various library branches.

keeps branch-related information, such as:

Branch number
Manager details
Address
Contact details

**Key SQL Queries & Data Analysis**

Several SQL queries are used in the project to examine and glean insightful information from the library's database:

Get the title, genre, and rental cost of every book that is available.
Sort the salaries of the employees in descending order.
Get the titles of the books and the customers who have owned them.
Show how many books there are in each category overall.
Retrieve workers with salaries over Rs. 50,000 along with their positions.
List the clients who signed up prior to 2022 but have not yet received their books.
Show the number of staff members in each library branch.
Customers who issued books in June 2023 should be retrieved.
Retrieve book titles that fall under the "History" category.
List the branches that employ more than five people.

**Excel Integration for Reporting & Visualization**

Excel is used for SQL data processing and visualization in order to improve data representation. The Excel dashboards and reports shown below are produced:

The Book Availability Report indicates how many books are available in each category.
Employee Salary Distribution: A visual representation of the differences in pay between employees.
A report that displays both active and inactive clients is called the Customer Issuance Trend.
Branch-Wise Employee Count: shows the number of employees in each branch.
The quantity of books released each month is tracked in the Monthly Issuance Report, a pivot table.
Based on the frequency of issuance, the Top Issued Books Chart shows which books are the most popular.

**Conclusion**

This SQL and Excel-based library management system offers a systematic and effective approach to overseeing a library's day-to-day operations.  The project increases decision-making, efficiency, and library resource accessibility by combining Excel for visualization and SQL queries for structured data management.
