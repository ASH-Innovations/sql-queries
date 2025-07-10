✅ 1. Install SQL Server (Developer Edition - Free)
🔗 Download from: SQL Server Developer Edition

Choose SQL Server 2022 Developer Edition.

Run the installer and select the Basic or Custom installation type.

Complete the installation with default options, or choose a named instance (e.g., SQLEXPRESS).

✅ 2. Install SQL Server Management Studio (SSMS)
🔗 Download SSMS: SSMS Download Page

This tool provides a GUI to connect to and manage your local SQL Server.

After installation, launch SSMS and connect to:

Server name: localhost or localhost\SQLEXPRESS (based on install)

Authentication: Use Windows Authentication or SQL Authentication (if configured)

✅ 3. (Optional) Install Azure Data Studio
🔗 Download Azure Data Studio: Azure Data Studio

A lightweight alternative to SSMS with better support for notebooks and extensions.

✅ 4. Verify SQL Server is Running
Open SQL Server Configuration Manager.

Check if the SQL Server instance (MSSQLSERVER or SQLEXPRESS) is Running.

Start it manually if not.

✅ 5. Run Your First Query
Open SSMS

Connect to the SQL Server instance.

Click New Query and run:

sql
Copy
Edit
SELECT @@VERSION;
This confirms SQL Server is up and running.
====================================================================================================================================================

# MS SQL Practice Repository
Ideal for QA professionals preparing for SQL-based interview questions, with examples covering essential database concepts and scenarios.
## Contents
- **Basic SQL Queries**: Simple SELECT statements, WHERE clauses, and filtering data.
- **Aggregations and Grouping**: Examples with `GROUP BY`, `COUNT`, `SUM`, `AVG`, and more.
- **Joins**: Inner joins, left/right joins, and full outer joins.
  
## How to Use

1. **Clone the Repository**:
   https://github.com/ASH-Innovations/sql-queries.git
