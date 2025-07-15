#  AI-Based Resume Screening System (Python + NLP)

This project is an AI-powered tool to automatically screen and rank resumes based on their relevance to a Job Description (JD).
It simulates a real-world HR tech solution used by recruitment platforms and companies.

---

##  Features

- Accepts resumes in PDF or DOCX format
- Cleans and preprocesses resume and JD text using NLP
- Extracts key sections: Skills, Education, Experience
- Calculates match score using TF-IDF + cosine similarity
- Outputs a ranked list in `results.csv`
- GUI interface with Tkinter for easy use

---

##  Folder Structure

```
resume_screening_project/
├── resumes/                  # Folder with PDF or DOCX resumes
├── job_description.txt       # Input job description file
├── resume_screening.py       # Main program file
├── results.csv               # Output (generated after run)
├── requirements.txt          # List of required packages
└── README.md                 # This documentation
`


##  Tech Stack

- Python 3
- Tkinter
- PyMuPDF
- python-docx
- scikit-learn
- pandas
- regex (re)

---
