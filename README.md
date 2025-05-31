
# 🧪 Medical Laboratory System Database

## 📌 Project Overview

This project is a complete **Medical Laboratory Database System** designed and implemented using **MySQL**. It was developed by three biotechnology students as a part of their academic coursework. The system is built to manage and organize data related to laboratorians, patients, medical tests, test results, and the components used in those tests.

## 👩‍💻 Team Members

- Sama Hazem — 231002053  
- Sara Ahmed — 231000777  
- Maria Amgad — 231001529  

## 🧠 Key Features

- Structured relational database schema using MySQL
- Entity-Relationship Design (ERD)
- SQL scripts for creating tables and inserting sample data
- Views for dynamic queries and reporting
- UI interface for adding and viewing data dynamically (via Google Colab)

## 🏗️ Database Design

### Main Entities:

- **Laboratorian**: ID, Name, Phone, Address  
- **Patient**: PatientID, Name, Phone, Address, Birth Date, Job  
- **Component**: ComponentID, Name, Available Quantity, Minimum Quantity  
- **Medical Test**: TestID, Name, Price, Related Component  
- **Test Result**: TestID, Date, PatientID, LaboratorianID, Result  

### Relationships:

- One patient can have many test results  
- One laboratorian can handle many test results  
- One medical test can be used in many test results  
- One component can be linked to many medical tests  

## 🧾 SQL Highlights

- **Database Creation**: `CREATE DATABASE medical_lab;`
- **Tables**: Laboratorian, Patient, Component, Medical_Test, Test_Result
- **Views**:
  - `CBC_test`: Lists patients who took a CBC test in 2024
  - `Low_components`: Lists components below minimum quantity
  - `Price`: Calculates total money paid by a specific patient since 2022

## 📊 Sample Queries

- Total money paid by patient with ID `12527` in the last 3 years
- Components that need restocking
- Patients who took specific tests

## 🖥️ User Interface

A simple UI is available to interact with the database dynamically.  
🔗 [Google Colab Interface](https://colab.research.google.com/drive/1GtHM_jImXUGhzHukm_w9KCdj4wezdPqZ?usp=sharing)

## 📽️ Presentation

The project was presented using a PowerPoint that outlines the process:
- ERD Design
- SQL Schema
- Data Insertion
- Relational Mapping
- UI Demonstration

## ✅ Conclusion

This project demonstrates how a well-structured relational database can be used to manage complex medical lab data efficiently. It combines theoretical design with practical implementation and user interaction.
