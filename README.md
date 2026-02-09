# Data Migration & Data Modelling

## 📌 Project Overview
This project showcases an end-to-end **data migration, data modelling, and validation** workflow using **SQL Server**.  
The goal was to migrate referral data from Excel into a structured database, apply business rule transformations, normalize the data model, and ensure data quality for analytics and reporting.

---

## 🛠️ Tools & Technologies
- SQL Server  
- ETL (INSERT INTO … SELECT)  
- Data Modelling (Fact & Dimension Tables)  
- Data Validation & Testing  
- Documentation (Test Reports)

---

## 🗄️ Database Details
- **Database:** NxzenDb  
- **Source Table:** source_data  
- **Destination Fact Table:** destinationn_data  
- **Lookup (Dimension) Tables:**  
  - Referral Status  
  - Job Category  
  - Referral Type  
  - Enquiry Type  
  - Planner  
  - Distribution Planner  
  - Customer Licence Type  
  - Postcode  
  - DNO  

---

## 🔄 Project Workflow

### 1️⃣ Data Migration
- Imported Excel data into SQL Server as a source table.
- Migrated data into the destination fact table using `INSERT INTO … SELECT`.
- Applied transformation logic during migration to meet business requirements.

### 2️⃣ Data Modelling
- Designed a centralized fact table for referral transactions.
- Identified repeating attributes and moved them into lookup tables.
- Implemented surrogate keys and one-to-many relationships.
- Populated foreign keys using JOIN-based update statements.

### 3️⃣ Business Rule Implementation
- Referral ID generation and formatting  
- Job category and enquiry type mapping  
- Referral type and referral status classification  
- Planner and distribution planner logic  
- Site address prefix handling  

---

## ✅ Data Validation & Testing
- Record count validation (source vs destination)
- Business rule validation using SQL queries
- Lookup table uniqueness and population checks
- Foreign key and referential integrity validation
- Mandatory field and data quality checks

All validation results were captured in **test reports** for audit and verification.

---

## 📊 Key Outcomes
- Successful data migration with **no data loss**
- Fully normalized and scalable data model
- Accurate business rule transformations
- High data quality and referential integrity
- Analytics-ready dataset suitable for BI tools like Power BI

---

## 🎯 Use Case
This project is ideal for demonstrating:
- SQL Server ETL and data migration skills  
- Data modelling and normalization concepts  
- Data validation and quality assurance  
- Preparation of analytics-ready datasets  

---


