# Career Path Analysis to be Data Analyst, Data Engineer and Data Scientist in SEEK

**Date: 24/03/2022**

**Brief Introduction**:

This project is to extract, clean, explore and analyze job description data of three popular job titles -- Data Analyst, Data Engineer and Data Scientist, in recent couple of months from the SEEK website. The purpose of this project is to have a quick look at the hottest required technical and soft skills in the job market and help provide career path references for people who would like to be a Data Analyst, Data Engineer, or Data Scientist.

**Programming Environment**: Python 3.8 and Jupyter Notebook

**Tools used**:
- Data Extraction, Data Cleaning and Data Wrangling: PyCharm
- Data Wrangling and Database Management: DB Browser for SQLite3 and Elephant DB for PostgreSQL
- Data Visualization: Power BI and Tableau

## Table of Contents

[1.Introduction](#sec_1)

- [1.1 Project Objective](#sec_1.1)
- [1.2 Target Audience](#sec_1.2)
- [1.3 Project Assumption](#sec_1.3)
- [1.4 Key Insights](#sec_1.4)

[2.Data Wrangling and Methodology](#sec_2)

- [2.1 Data Cleaning](#sec_2.1)
- [2.2 Dimensional Modeling Method](#sec_2.2)
- [2.3 Data Extracting](#sec_2.3)
- [2.4 Term Frequency Analysis](#sec_2.4)
- [2.5 Documentary Frequency Analysis](#sec_2.5)
- [2.6 Requirements & Getting Started](#sec_2.6)

[3.Exploratory Data Analysis](#sec_3)

- [3.1 Required Skills for Data Analyst](#sec_3.1)
- [3.2 Required Skills for Data Engineer](#sec_3.2)
- [3.3 Required Skills for Data Scientistg](#sec_3.3)
- [3.4 Carrier Path](#sec_3.4)

[4.Conclusion](#sec_4)

[5.References](#sec_5)

## 1. Introduction <a class="anchor" id="sec_1"></a>
### 1.1 Project Objective <a class="anchor" id="sec_1.1"></a>
This project extract, clean, explore and analyze job description data of three popular job titles -- Data Analyst, Data Engineer and Data Scientist, in recent couple of months from SEEK website. This GitHub repo contains all the codes and datasets for this project. The objectives of this project are:

- **Clean dirty salary and datetime data, then transform them for analytics**.

- **Exploratory data analysis**, e.g. 
    - ✨find the hottest technical and soft skills for different job titles -- Data Analyst, Data Engineer and Data Scientist.
    - ✨analyze the salary differences for different job titles and job types.
    - ✨analyze the available positions and required technical skills in different regions.
    - ✨analyze the possible relationship between salary range and required technical skills.

- **Provide career path references for people who would like to be a Data Analyst, Data Engineer or Data Scientist**.

### 1.2 Target Audience <a class="anchor" id="sec_1.2"></a>
#### People who would like to be a Data Analyst, Data Engineer, or Data Scientist.
### 1.3 Project Assumption <a class="anchor" id="sec_1.3"></a>
- Assuming that the SEEK website can represent the current situation and trends of job market in Australia.
- Assuming the recruitment data on the SEEK website is accurate.
- Assume that people always would like to put the most important information first, for example, the higher the position in the job advertisement. In other words, the earlier the relevant skills appear means that they are more important to the company.

### 1.4 Key Insights <a class="anchor" id="sec_1.4"></a>
This project extract job description data of three popular job titles -- Data Analyst, Data Engineer and Data Scientist, in recent couple of months from SEEK website. The job locations include eight major cities in Australia – Sydney, Melbourne, Perth, Brisbane, Gold Coast, Adelaide, ACT and Hobart. Among them, there are 2224 job advertisements for Data Analyst, 1180 job advertisements for Data Engineer, and 529 job advertisements for Data Scientist. From the analyzed results, the main conclusions can be summarized as follows: 
#### Top hottest required skills for Data Analyst: `SQL, Excel, Power BI, Tableau, Python, Data Visualization, Reporting and Communication Skills`
#### Top hottest required skills for Data Engineer:`Cloud, SQL, AWS, Python, Azure, Data Pipeline, ETL/ELT, Communication Skills`
#### Top hottest required skills for Data Scientist: `Python, Communication Skills, Machine Learning, Data Science, Statistics, Research, Computer Science, SQL`
