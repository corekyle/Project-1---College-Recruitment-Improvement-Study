# CCM Computing Courses Entry Survey — Exploratory Data Analysis

## Overview & Purpose
This repository houses Project 1 for **CMP-262: Data Science Programming** at the County College of Morris (CCM). 

The primary goal of this project is to perform an **Exploratory Data Analysis (EDA)** on entry-level computing course survey datasets using Python. By uncovering patterns in student demographics, outreach effectiveness, pre-college experiences, and enrollment motivations, this study provides actionable, data-driven recommendations to help the **CCM Department of Information Technologies** improve its recruitment strategies and increase student enrollment—particularly among underrepresented groups.

---

## Project Workflow & Structure
This project follows a structured four-part Data Science and EDA lifecycle:

### 1. Data Study Questions (Part 1)
* Formulated targeted, answerable data science questions focused on **which**, **when**, **where**, and **why** students enroll in entry-level computing courses.
* Combined instructor-assigned baseline demographic questions with custom study questions evaluating marketing channels, pre-college outreach programs, and student motivations.

### 2. Data Exploration & Cleaning (Part 2)
* Performed initial structural inspection in Excel and programmatic exploration in Python using `pandas` (`describe()`, `info()`, `shape`, `dtypes`, `head()`, `tail()`, `sample()`).
* Executed systematic data cleaning:
  * Standardized all column names to lowercase snake_case format.
  * Removed irrelevant metadata columns (e.g., timestamps and unused free-text columns).
  * Condensed redundant categorical values (e.g., consolidating degree program variations into unified categories).
  * Handled missing (`NaN`) values carefully to preserve conditional survey branching logic without dropping valid rows.
* Exported the finalized dataset to `Majors Survey Results - Fall 2024 - Cleaned.csv`.

### 3. Data Analysis & Visualization (Part 3)
* Analyzed the cleaned Fall 2024 dataset using `pandas`, `matplotlib`, and `seaborn` to answer four core study questions.
* Created clear, well-labeled visualizations illustrating demographic distributions, top outreach sources for underrepresented students, pre-college event participation rates, and primary student motivators.

### 4. Peer Review & Plot Refinement (Part 4)
* Shared visualizations and analytical findings in class discussion forums to gather peer feedback and refine plot clarity, color accessibility, and storytelling impact.

---

## Key Findings & Recommendations
* **Demographic Gaps:** Women represent **16.8%** of students in entry-level computing courses, while traditional college-age students (18–20) account for over **70%** of enrollment. Targeted recruitment efforts should focus on expanding female and non-traditional adult participation.
* **High-Impact Information Channels:** Among underrepresented students, the **CCM Information Technologies Website (33.3%)** and **CCM Admissions (33.3%)** tied as the most effective information sources, followed by **High School Guidance Counselors (21.3%)**.
* **Effective Pre-College Touchpoints:** **Individual Campus Visits (22.8%)** and **Open Houses (22.3%)** achieved the highest pre-college participation rates, underscoring the value of in-person campus engagement.
* **Primary Enrollment Motivators:** Securing a job in the computing field (**64.5%**) and transferring to a 4-year bachelor's program (**53.8%**) are the strongest drivers behind student enrollment, suggesting recruitment messaging should highlight career placement outcomes and transfer articulation agreements.

---

## Repository Contents
* `Project_1_Part_2_Cleaning.ipynb` — Jupyter Notebook containing initial data exploration and pandas cleaning pipeline.
* `Project_1_Part_3_Analysis.ipynb` — Jupyter Notebook containing statistical breakdowns, visualizations, and recruitment insights.
* `Majors Survey Results - Fall 2024.csv` — Raw survey input dataset.
* `Majors Survey Results - Fall 2024 - Cleaned.csv` — Processed dataset ready for analysis.
* `README.md` — Project documentation and summary.

---

## Technologies & Libraries Used
* **Python 3.x**
* **Pandas** & **NumPy** (Data manipulation and cleaning)
* **Matplotlib** & **Seaborn** (Data visualization)
* **Jupyter Notebook** (Interactive development and documentation)