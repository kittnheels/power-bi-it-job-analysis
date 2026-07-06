
# IT Skills & Certifications Analysis

## Objective

Analyze technology job roles, required skills, and certifications using Power BI.

## Dataset

The dataset contains:

- Job Title
- Job Description
- Skills
- Certifications

## Data Quality Issues Identified

- Duplicate job titles due to capitalization differences
- Certification naming inconsistencies caused by different dash characters
- Duplicate counting caused by flattened data structure

## Data Modeling Approach

Created three logical entities:

- Jobs
- Skills_Table
- Certifications_Table

Relationships:

Jobs → Skills_Table

Jobs → Certifications_Table

## Measures Created

- Total Jobs (DISTINCTCOUNT)
- Distinct Skills
- Distinct Certifications
- Jobs per Skill
- Skill Coverage %

## Key Learnings

- Data cleaning with Power BI
- Relationship modeling
- Many-to-many relationship considerations
- Dashboard design

## Tools Used

- Power BI Desktop
- Power Query
- DAX
- GitHub
