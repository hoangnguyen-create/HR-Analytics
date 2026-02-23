# HR Analytics: Job Change of Data Scientists
### **Project Overview:**

This project implements an end-to-end ETL pipeline for an HR analytics use case involving job change behavior among data science candidates.

Six structured datasets were extracted, cleaned, transformed, and merged into a unified analytical dataset. The final output is a standardized, model-ready dataset designed to support further analysis or predictive modeling.

The project highlights hands-on experience in multi-source data integration, data cleaning, feature transformation, and pipeline structuring using Python.

### Data sources: 

**1. Enrollies' data:** https://docs.google.com/spreadsheets/d/1VCkHwBjJGRJ21asd9pxW4_0z2PWuKhbLR3gUHm-p4GI/edit?usp=sharing

As enrollies are submitting their request to join the course via Google Forms, we have the Google Sheet that stores data about enrolled students

**2. Enrollies' education:** https://assets.swisscoding.edu.vn/company_course/enrollies_education.xlsx

After enrollment everyone should fill the form about their education level. This form is being digitalized manually. Educational department stores it in the Excel format

**3. Enrollies' working experience:** https://assets.swisscoding.edu.vn/company_course/work_experience.csv

Another survey that is being collected manually by educational department is about working experience.

**4. Training hours:**

**Database credentials:** 
* Database type: MySQL
* Host: 112.213.86.31
* Port: 3360
* Login: etl_practice
* Password: 550814
* Database name: company_course
* Table name: training_hours

**5. City development index:** https://sca-programming-school.github.io/city_development_index/index.html

The City Development Index (CDI) is a measure designed to capture the level of development in cities. It may be significant for the resulting prediction of student's employment motivation.

**6. Employment:**

**Database credentials:**
* Database type: MySQL
* Host: 112.213.86.31
* Port: 3360
* Login: etl_practice
* Password: 550814
* Database name: company_course
* Table name: employment
