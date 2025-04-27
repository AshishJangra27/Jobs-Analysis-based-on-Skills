# Job Market Skill Requirements Analysis

<img src="https://raw.githubusercontent.com/AshishJangra27/Jobs-Analysis-based-on-Skills/refs/heads/main/poster.png" width="100%">

## 📌 Project Overview

This project analyzes **job market trends** focusing on:
- Identifying **common skills** across various job roles.
- Highlighting **key skills** for specific roles like **Data Analyst**.
- Extracting **important skills for HDFC Bank** jobs.
- Exploring the relationship between **years of experience** and **job availability**.

The insights are derived from a comprehensive dataset of job listings.

---

## 📊 Dataset Columns

- `job_role`: Designation or position title.  
- `company`: Company offering the job.  
- `experience`: Required years of experience.  
- `salary`: Offered salary (if disclosed).  
- `location`: Job location(s).  
- `rating`: Company rating.  
- `reviews`: Number of company reviews.  
- `resposibilities`: Key skills or responsibilities.

---

## 🔍 Approach

1. **Data Cleaning**:
   - Handle missing values.
   - Standardize skill names in the `resposibilities` column.
   - Extract numerical experience and salary ranges.

2. **Skill Analysis**:
   - Identify top recurring skills across all job listings.
   - Filter and analyze skills specific to:
     - **Data Analyst** roles.
     - **HDFC Bank**.

3. **Experience-Level Analysis**:
   - Analyze **years of experience** distribution.
   - Understand how experience correlates with job availability.

---

## 📈 Visual Insights

- **Top Job Responsibilities**:  
  Visualizations display the most in-demand skills across job listings.

- **Experience vs. Job Availability**:  
  Histograms highlight the concentration of job opportunities based on years of experience.

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/AshishJangra27/Jobs-Analysis-based-on-Skills.git
   ```
