# Resume / Candidate Screening System

## Project Overview

This project is a Machine Learning and NLP-based Resume Screening and Candidate Ranking System developed as part of **Future Interns - Machine Learning Task 3 (2026)**.

The system analyzes candidate resumes and compares them with a job description to identify the most suitable candidates for a specific role.

The target role used in this project is:

**Machine Learning Engineer**

---

## Objective

The goal of this project is to build a system that can:

- Read and process resume text
- Clean and preprocess resume data
- Extract relevant technical skills
- Compare resumes with a job description
- Calculate resume similarity scores
- Identify matched skills
- Identify missing skills
- Rank candidates based on their suitability

---

## Dataset

The project uses the Resume Dataset containing resumes from multiple professional categories.

The dataset contains:

- Resume text
- Candidate category

The resume text is processed using NLP techniques for candidate screening and ranking.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Regular Expressions (Regex)
- Scikit-learn
- TF-IDF Vectorizer
- Cosine Similarity
- Matplotlib
- Natural Language Processing (NLP)
- Jupyter Notebook
- VS Code

---

## Job Description

The system evaluates candidates for the role of:

### Machine Learning Engineer

Important skills considered include:

- Python
- Machine Learning
- Deep Learning
- Data Science
- NLP
- Pandas
- NumPy
- Scikit-learn
- TensorFlow
- PyTorch
- SQL
- Data Analysis
- Data Visualization
- Git

---

## Workflow

### 1. Resume Text Cleaning

Resume text is cleaned by:

- Converting text to lowercase
- Removing URLs
- Removing unnecessary special characters
- Removing extra spaces

### 2. Skill Extraction

A predefined list of technical skills is used to identify relevant skills from each resume.

### 3. Resume Similarity

TF-IDF is used to convert resumes and the job description into numerical vectors.

Cosine Similarity is then used to measure how closely each resume matches the job description.

### 4. Skill Matching

The system identifies:

- Matched Skills
- Missing Skills
- Number of matched skills

### 5. Candidate Ranking

A final score is calculated using:

- Resume similarity score
- Skill match score

Candidates are then ranked from highest to lowest score.

---

## Candidate Scoring

The final candidate score is calculated using:

- 70% Resume Similarity Score
- 30% Skill Match Score

This helps balance overall resume relevance with direct skill matching.

---

## Visualizations

The project generates:

1. Top 10 Candidates Ranking
2. Resume Similarity Scores
3. Skill Match Comparison
4. Candidate Category Distribution

---

## Business Value

This system can help recruiters and HR teams:

- Reduce manual resume screening
- Quickly identify suitable candidates
- Compare candidates objectively
- Identify missing skills
- Shortlist candidates faster
- Improve recruitment efficiency

This project demonstrates how NLP and Machine Learning techniques can support real-world HR and recruitment operations.

---

## Project Structure

```text
Task_3_Resume_Screening
│
├── data
│   ├── Resume.csv
│   └── candidate_ranking_results.csv
│
├── notebooks
│   └── resume_screening.ipynb
│
├── images
│   ├── top_10_candidates.png
│   ├── resume_similarity_scores.png
│   ├── skill_match_comparison.png
│   └── top_candidate_categories.png
│
└── README.md



Author

Pratham Singh

Future Interns - Machine Learning Internship (2026)

> Note: The original Resume.csv dataset is not included in this repository due to file size limitations. The dataset can be downloaded from the Kaggle Resume Dataset.
