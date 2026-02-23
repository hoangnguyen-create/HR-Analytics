# HR Analytics: Job Change of Data Scientists
### **Project Overview:**

This project implements an end-to-end ETL pipeline for an HR analytics use case involving job change behavior among data science candidates.

Six structured datasets were extracted, cleaned, transformed, and merged into a unified analytical dataset. The final output is a standardized, model-ready dataset designed to support further analysis or predictive modeling.

The project highlights hands-on experience in multi-source data integration, data cleaning, feature transformation, and pipeline structuring using Python.

Link to whole project via Google Collab: [https://colab.research.google.com/drive/1T7gahFWhTsPRMcY8n0sP1AI-MDGGuujz?usp=sharing](https://colab.research.google.com/drive/1ciyhHlerKPY3DMGYNVX62pakmfYJ_N_W#scrollTo=uOeTyTRJgOgH)

### Data sources: 

**1. Enrollies' data:** https://docs.google.com/spreadsheets/d/1VCkHwBjJGRJ21asd9pxW4_0z2PWuKhbLR3gUHm-p4GI/edit?usp=sharing

As enrollies are submitting their request to join the course via Google Forms, we have the Google Sheet that stores data about enrolled students

**2. Enrollies' education:** https://assets.swisscoding.edu.vn/company_course/enrollies_education.xlsx

After enrollment everyone should fill the form about their education level. This form is being digitalized manually. Educational department stores it in the Excel format

**3. Enrollies' working experience:** https://assets.swisscoding.edu.vn/company_course/work_experience.csv

Another survey that is being collected manually by educational department is about working experience.

**4. Training hours:** Database credentials were provided in a secure local environment.

**5. City development index:** https://sca-programming-school.github.io/city_development_index/index.html

The City Development Index (CDI) is a measure designed to capture the level of development in cities. It may be significant for the resulting prediction of student's employment motivation.

**6. Employment:** Database credentials were provided in a secure local environment.

### Pipeline summary: 

#### ETL Pipeline

### Extract
- Google Sheets (Enrollies data)
- Excel file (Education data)
- CSV file (Work experience)
- MySQL database (Training hours, Employment)
- Public CDI dataset

### Transform
- Standardized column naming
- Removed duplicates
- Handled missing values
- Encoded categorical variables
- Merged 6 datasets into unified table

### Load
- Exported clean dataset to CSV
- Final dataset ready for analytics or modeling


