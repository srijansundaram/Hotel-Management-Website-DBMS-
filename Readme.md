# Getaway Mansion Hotel Management System (SQL)

This project contains SQL scripts for managing the database of the Getaway Mansion Hotel. It includes table creation, data insertion, and queries for retrieving hotel management information.

## Files

- **table creation.sql**  
  Creates all necessary tables for the hotel management system, including `admin`, `receptionist`, `customer`, `rate`, `room`, and `transactiondetail`.

- **table insertion.sql**  
  Inserts sample data into all tables for testing and demonstration purposes.

- **table print.sql**  
  Contains SQL queries to display the contents of all tables and to calculate transaction details such as duration of stay and total payment.

- **onecompedit.sql**  
  A combined script for creating tables, inserting data, and running select queries. Uses SQL Server syntax (e.g., `IDENTITY` for auto-increment).

- **Get-Away-Mansion-Hotel-Management-System.pptx**  
  Presentation file describing the project (not SQL).

- **Untitled Workspace.jpg**  
  Image file, possibly related to the project.

## Usage

1. **Create the Database and Tables**  
   Run `table creation.sql` to set up the database and tables.

2. **Insert Sample Data**  
   Run `table insertion.sql` to populate the tables with sample data.

3. **View Data and Reports**  
   Run `table print.sql` to view all records and transaction summaries.

4. **All-in-One Script**  
   Alternatively, use `onecompedit.sql` for a combined workflow (suitable for SQL Server).

## Notes

- The scripts are written for both MySQL (`AUTO_INCREMENT`) and SQL Server (`IDENTITY`).  
  Use the appropriate script for your database system.
- Foreign key constraints ensure data integrity between tables.
- Transaction reports include duration of stay and total payment calculations.

## License

This project