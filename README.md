
Hospital Management System using SQL

📌 Project Overview

The Hospital Management System is a database project developed using SQL to manage hospital operations, including departments, doctors, patients, appointments, prescriptions, and billing information.

The project demonstrates relational database design, data manipulation, and SQL queries to retrieve useful information for hospital management.

🎯 Objectives

Manage hospital departments and doctor details.

Store and retrieve patient information.

Schedule and track patient appointments.

Maintain prescription records.

Manage billing information and payment statuses.

Generate useful reports using SQL queries.

🛠️ Technologies Used

Database: MySQL

Language: SQL

Concepts: DDL, DML, SELECT queries, JOINs, aggregate functions, UPDATE, DELETE, primary keys, and foreign keys.

🗂️ Database Tables

The project contains six tables:

Table Name

Description

Departments

Stores department details.

Doctors

Stores doctor information and department assignments.

Patients

Stores patient details.

Appointments

Maintains patient appointments with doctors.

Prescriptions

Stores medicines and dosage instructions linked to appointments.

Billing

Maintains patient bills and payment statuses.

🔗 Database Relationships

A department can have multiple doctors.

A patient can have multiple appointments.

A doctor can attend multiple appointments.

An appointment can have multiple prescriptions.

A patient can have multiple billing records.

⚙️ Features Implemented:

Create the hospital database and tables.

Insert sample records into all six tables.

Retrieve patient, doctor, and appointment information.

Combine patient, doctor, and appointment data using JOIN operations.

Identify patients with pending bills.

Count the total number of patients.

Calculate revenue collected from paid bills.

Retrieve doctors belonging to a specific department.

Update appointment statuses.

Delete prescription records.
