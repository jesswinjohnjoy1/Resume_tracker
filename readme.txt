📄 Resume Shortlisting System
🚀 Project Overview

The Resume Shortlisting System is an AI-powered application designed to automatically screen and shortlist resumes based on job requirements. It reduces manual effort in the recruitment process by using Natural Language Processing (NLP) and Machine Learning (ML) techniques to match resumes with job descriptions.

This system helps recruiters quickly identify the most suitable candidates by analyzing skills, experience, and keywords present in resumes.

🎯 Objectives

Automate the resume screening process

Reduce human bias in shortlisting

Improve accuracy and efficiency in recruitment

Rank resumes based on job relevance

🛠️ Technologies Used

Programming Language: Python

Libraries & Tools:

Pandas

NumPy

Scikit-learn

NLTK / SpaCy

Machine Learning Algorithms:

TF-IDF Vectorization

Naive Bayes / Support Vector Machine (SVM)

Database (Optional):

MySQL / SQLite

Development Environment:

Google Colab / Jupyter Notebook

🧠 How It Works

Upload multiple resumes (PDF / DOCX / text format)

Preprocess resume text (cleaning, tokenization, stop-word removal)

Convert resumes and job descriptions into numerical vectors using TF-IDF

Apply ML classification or similarity matching

Rank resumes based on relevance score

Shortlist top candidates automatically

🔄 System Workflow
Resume Upload → Text Preprocessing → Feature Extraction (TF-IDF)
→ ML Model → Resume Scoring → Shortlisting

📂 Project Structure
Resume-Shortlisting-System/
│
├── dataset/
│   ├── resumes/
│   └── job_descriptions/
│
├── preprocessing.py
├── feature_extraction.py
├── model_training.py
├── resume_ranking.py
├── main.py
├── requirements.txt
└── README.md

✅ Features

Automated resume screening

Job-specific resume matching

Keyword and skill-based filtering

Resume ranking system

Scalable for large datasets

📊 Output

Relevance score for each resume

Ranked list of candidates

Shortlisted resumes based on threshold

🔮 Future Enhancements

Web interface using React

Backend integration with Spring Boot / Flask

Advanced NLP using BERT or Transformers

Resume parsing with section-wise analysis

Admin dashboard for recruiters

📌 Use Cases

Recruitment agencies

HR departments

Campus placement cells

Job portals

👤 Author

Jesswin Anto
Electronics and Communication Engineering
Aspiring Software & AI/ML Engineer