# Healthcare Database Project

## Project Overview
This project is a healthcare database built using MySQL to organize and manage doctor information. It stores details about doctors, their specialties, insurance information, availability for new patients, and professional contact information.

The project demonstrates the use of SQL and relational databases to organize healthcare provider data and make it easier to query and analyze.

## Database Features
The doctors database includes information such as:

- **Doctor ID:** Unique identifier for each doctor.
- **Gender:** Doctor's gender, as recorded in the dataset.
- **Insurance:** Insurance plans accepted by the doctor.
- **New Patients:** Indicates whether the doctor is accepting new patients.
- **Specialty 1:** Primary medical specialty.
- **Specialty 2:** Additional medical specialty.
- **Specialty 3:** Another additional specialty, if available.
- **License:** Professional license information.
- **Phone:** Doctor's contact phone number.

The database may also include hospital information or other healthcare-related tables.

## Technologies Used
- MySQL
- MySQL Workbench
- SQL
- Git and GitHub
- MAMP


## How to Import the Database

1. Install MySQL Server and MySQL Workbench.
2. Open MySQL Workbench and connect to your MySQL server.
3. Select **File → Open SQL Script** to inspect the SQL file, or use **Server → Data Import** to import the dump.
4. Follow the import instructions, selecting the appropriate target schema if needed.
5. Refresh the **SCHEMAS** panel to view the database tables.

## Example Queries

Find doctors accepting new patients:

```sql
SELECT *
FROM doctors
WHERE `new-patients` = 'Yes';
```

List doctors by specialty:

```sql
SELECT *
FROM doctors
WHERE `speciality one` = 'Cardiology';
```

*Note: These examples assume the table is named `doctors`, the column names match those shown, and the stored values use the examples above. Adjust them to match your actual schema.*

## Project Goals
- Organize healthcare provider information.
- Explore doctor specialties and insurance participation.
- Identify doctors accepting new patients.
- Practice SQL queries and database management.
- Demonstrate database skills in a GitHub portfolio.

## Privacy and Data Protection
Before publishing this project, verify that the dataset does not contain confidential personal information, credentials, or other data that should not be public. Use appropriately licensed, public, or anonymized data.

## Author
Susan Noorzai
