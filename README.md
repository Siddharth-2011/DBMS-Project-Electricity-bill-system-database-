# DBMS-Project-Electricity-bill-system-database-
**Electricity Bill System Database Project**
The Electricity Bill System Database project is designed to efficiently manage and generate electricity bills for users. This project incorporates various concepts of database management systems, including SQL, PL/SQL, foreign keys, primary keys, entity relationship diagrams (ERDs), and more. By entering user details, the system generates accurate and comprehensive electricity bills. Each user is assigned a user type (commercial or retail), an electricity board, and a tariff. The system also maintains user accounts, which include the previous balance and current bill for accurate billing calculations.

**Features**
The Electricity Bill System Database project offers the following features:
1. User Management: Add, update, and delete user details such as name, address, and contact information.
2. User Type Assignment: Assign each user a type, either commercial or retail, based on their electricity usage.
3. Electricity Board Assignment: Associate each user with a specific electricity board to determine the service provider.
4. Tariff Assignment: Assign a tariff to each user based on their consumption pattern to calculate accurate bills.
5. Account Management: Track and maintain user accounts, including the previous balance and current bill.
6. Bill Generation: Generate electricity bills for users by considering their consumption, user type, tariff, and account balance.

**Database Schema**
The database schema for the Electricity Bill System includes the following tables:
1. Users: Stores user details such as user ID, name, address, and contact information.
2. UserTypes: Contains user type information, including user type ID and description (commercial or retail).
3. ElectricityBoards: Stores details about electricity boards, including board ID and name.
4. Tariffs: Stores tariff information, including tariff ID, description, and rate details.
5. Accounts: Tracks user accounts, including account ID, user ID, previous balance, and current bill.
6. Bills: Stores generated electricity bills, including bill ID, user ID, billing period, and amount.

**Project Structure**
The repository is structured as follows:
/codes: This directory contains the SQL and PL/SQL codes for creating the database schema and implementing various operations.
/er diagram: This directory contains the image of the Entity Relationship diagram.
/project report: This directory includes additional documentation, such as screenshots and tables to assist with project setup and usage.

Enjoy managing and generating electricity bills efficiently with the Electricity Bill System Database project!
