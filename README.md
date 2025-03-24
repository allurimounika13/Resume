# AI Resume Screening & Candidate Ranking System

## Overview
This project is an AI-powered resume screening and ranking system designed to assist recruiters in evaluating resumes efficiently. It utilizes *TF-IDF vectorization* and *cosine similarity* to compare resumes with a given job description, ranks candidates based on relevance, and provides personalized suggestions for improvement.

## Features
- Upload multiple resumes in *PDF format*.
- Enter a *job description* for comparison.
- *AI-powered ranking* of resumes based on similarity.
- *Dynamic feedback* with suggestions to improve resumes.
- *User-friendly interface* built with Streamlit.

## Technologies Used
- *Python*: Backend logic.
- *Streamlit*: Web application framework.
- *PyPDF2*: Extracting text from PDF resumes.
- *scikit-learn*: Machine learning model for text comparison.
- *Pandas & NumPy*: Data processing and manipulation.

## Installation Guide
### Prerequisites
Ensure you have Python installed (preferably Python 3.8 or later). You can download it from [Python Official Website](https://www.python.org/).

### Steps
1. *Clone the repository*
   sh
   git clone https://github.com/your-username/resume-screening.git
   cd resume-screening
   
2. *Create a virtual environment* (optional but recommended)
   sh
   python -m venv env
   source env/bin/activate   # On macOS/Linux
   env\Scripts\activate      # On Windows
   
3. *Install dependencies*
   sh
   pip install -r requirements.txt
   
4. *Run the Streamlit app*
   sh
   streamlit run app.py
   

## How It Works
1. *Upload PDF Resumes*: The system extracts text from resumes.
2. *Enter a Job Description*: The entered job description is analyzed.
3. *Ranking System*: AI ranks resumes based on similarity.
4. *Improvement Suggestions*: Provides feedback to enhance resumes.
