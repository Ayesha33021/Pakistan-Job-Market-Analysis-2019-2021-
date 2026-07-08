# Pakistan Job Market Analysis (2019–2021)

## 📌 Project Overview

This project presents an exploratory data analysis (EDA) of the Pakistan job market using a Kaggle dataset containing job postings from **2019 to 2021**. The objective is to identify hiring trends, the most in-demand industries, leading employers, hiring locations, experience requirements, and the technical skills most frequently requested by employers.

The analysis demonstrates a complete data analytics workflow, including data cleaning, preprocessing, visualization, and text mining of job descriptions to extract employer-required skills.

---

## 🎯 Objectives

* Analyze hiring trends across Pakistan.
* Identify the most common job categories.
* Determine the top hiring companies.
* Discover the cities with the highest employment opportunities.
* Analyze experience requirements.
* Explore monthly hiring trends from 2019–2021.
* Extract the most demanded technical skills using Natural Language Processing (NLP).

---

## 📂 Dataset

* **Source:** Kaggle
* **Time Period:** 2019–2021
* **Country:** Pakistan

### Dataset Features

* Job Name
* Company Name
* Job Type
* Department
* Experience Required
* Job Description
* Location
* Date Posted

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Regular Expressions (Regex)
* Collections (Counter)
* Jupyter Notebook

---

## 📊 Project Workflow

### 1. Data Cleaning

* Removed duplicate records
* Handled missing values
* Standardized categorical values
* Converted date columns into:

  * Year
  * Month
  * Day Name
  * Quarter
* Cleaned job descriptions for text analysis

---

### 2. Exploratory Data Analysis (EDA)

The following analyses were performed:

* Top Job Categories
* Top Hiring Companies
* Top Hiring Locations
* Experience Requirement Distribution
* Monthly Hiring Trends
* Quarterly Hiring Trends
* Day-wise Job Posting Trends

---

### 3. Text Mining

Natural Language Processing (NLP) techniques were applied to the **Job Description** column to identify technical skills requested by employers.

A custom skill dictionary was developed to detect technologies including:

* Programming Languages
* Web Technologies
* Frameworks
* Databases
* Cloud Platforms
* Data Analytics Tools
* Mobile Development
* DevOps Tools
* Digital Marketing Technologies

---

## 📈 Key Findings

### 💼 Hiring Trends

* The dataset shows strong hiring activity across multiple industries during 2019–2021.
* Hiring demand varies across months, indicating seasonal recruitment patterns.

### 🏢 Companies

* A small number of companies account for a significant share of job advertisements, suggesting concentrated recruitment among major employers.

### 📍 Locations

* Major metropolitan cities dominate the job market, with most vacancies concentrated in Pakistan's largest economic hubs.

### 👨‍💼 Experience

* Many job postings target candidates with prior work experience, while entry-level opportunities are available but comparatively fewer.

### 💻 Most In-Demand Technical Skills

The skill extraction analysis identified the following technologies among the most frequently requested:

* PHP
* WordPress
* SEO
* Android Development
* Laravel
* HTML
* React
* JavaScript
* CSS
* Digital Marketing
* iOS Development
* Unity
* Photoshop
* MVC
* MySQL

These results indicate that employers place strong emphasis on **web development**, **mobile application development**, **content management systems**, and **digital marketing**.

---

## 💡 Business Insights

* Web development technologies remain highly demanded, particularly PHP, Laravel, JavaScript, React, HTML, and CSS.
* Content management platforms such as WordPress continue to play a major role in the Pakistani software industry.
* Digital marketing skills, especially SEO, are widely requested across different business sectors.
* Mobile application development using Android and iOS technologies represents a growing employment area.
* Employers increasingly seek candidates with a combination of technical expertise and practical experience.

---

## 📌 Recommendations

### For Students

* Learn modern web development technologies such as HTML, CSS, JavaScript, React, PHP, and Laravel.
* Build practical projects to demonstrate your skills through a portfolio.
* Gain experience with databases such as MySQL and version control tools like Git.

### For Job Seekers

* Strengthen both technical and communication skills.
* Tailor resumes to match the specific technologies requested in job descriptions.
* Focus on high-demand technologies identified in this analysis.

### For Educational Institutions

* Update curricula to include industry-relevant technologies and frameworks.
* Incorporate practical, project-based learning to improve graduate employability.
* Expand training in digital marketing, cloud computing, and mobile application development.

---

## 📁 Project Structure

```text
Pakistan-Job-Market-Analysis/
│
├── Data/
│   ├── raw_dataset.csv
│   └── cleaned_dataset.csv
│
├── Images/
│   ├── Top Job Types.png
│   ├── Top Companies.png
│   ├── Top Locations.png
│   ├── Experience Distribution.png
│   ├── Monthly Hiring Trend.png
│   └── Top Skills.png
│
├── Pakistan Job Market Analysis.ipynb
├── README.md
└── requirements.txt
```

---

## 📷 Visualizations

The project includes visualizations covering:

* Job Category Distribution
* Top Hiring Companies
* Hiring Locations
* Experience Requirements
* Monthly Hiring Trends
* Quarterly Hiring Trends
* Day-wise Hiring Trends
* Top Technical Skills Required by Employers

---

## 📌 Conclusion

This project provides a comprehensive overview of Pakistan's job market between 2019 and 2021. Through data cleaning, exploratory data analysis, and NLP-based skill extraction, it highlights the technologies, industries, and locations driving employment demand. The findings can help students, job seekers, educators, and recruiters better understand market trends and align their skills or hiring strategies with current employer requirements.
