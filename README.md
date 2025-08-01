# USHealthcare-sql_mini_project
Filtering (WHERE, ORDER BY, LIMIT)  Aggregations (SUM, COUNT, AVG) with GROUP BY &amp; HAVING  Joins (INNER JOIN, Multiple Table Joins)  Window Functions (RANK)

Schema (PostgreSQL v17)
Tables:

patients → Patient details (ID, name, age, gender, city)

doctors → Doctor details (ID, name, specialty, city)

appointments → Appointment details (patient, doctor, date, fee)

prescriptions → Prescribed medicines (appointment, medicine, quantity, price)

See schema.sql for full table creation and sample data insert statements.

Skills Demonstrated
SQL Filtering & Sorting

Aggregate Functions (SUM, COUNT, AVG)

GROUP BY + HAVING clauses

Multiple Table Joins

Window Functions (RANK)

Query Optimization Practices


Project Structure

/Healthcare_SQL_Project
│── schema.sql           # Table creation & sample data
│── queries.sql          # All project queries
│── README.md            # Project documentation

