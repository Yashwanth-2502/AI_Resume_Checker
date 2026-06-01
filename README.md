# AI Resume Checker

An intelligent ATS (Applicant Tracking System) Resume Analyzer built with Python that evaluates resumes against job descriptions, calculates ATS compatibility scores, identifies missing skills, and provides actionable recommendations to improve job application success rates.

## Features

* PDF Resume Parsing and Text Extraction
* ATS Compatibility Score Calculation
* Job Description Matching
* Missing Skills Identification
* Resume Improvement Suggestions
* Machine Learning-Based Similarity Analysis
* Interactive Jupyter Notebook Support
* Easy-to-Use Python Implementation

## Technologies Used

* Python
* PDFPlumber
* Scikit-learn
* Pandas
* NumPy
* TF-IDF Vectorization
* Cosine Similarity

## How It Works

1. Upload or provide a PDF resume.
2. Enter a target job description.
3. The system extracts and processes resume content.
4. TF-IDF vectorization converts text into numerical representations.
5. Cosine similarity calculates the ATS match percentage.
6. Missing skills are identified by comparing resume content with job requirements.
7. Personalized recommendations are generated to improve the resume.

## Project Structure

```text
AI-Resume-Checker/
│
├── AI_Resume_Checker.ipynb
├── resume.pdf
├── requirements.txt
└── README.md
```

## Installation

```bash
pip install pdfplumber scikit-learn pandas numpy
```

## Usage

1. Open the Jupyter Notebook.
2. Update the resume file path.
3. Enter the desired job description.
4. Run all cells.
5. View ATS score, missing skills, and suggestions.

## Sample Output

```text
ATS Score: 82.45%

Missing Skills:
• AWS
• Docker

Suggestions:
• Add measurable achievements
• Include relevant missing skills
• Align projects with job requirements
```

## Future Enhancements

* Resume Ranking System
* AI-Powered Resume Rewriting
* Keyword Optimization
* Multi-Resume Comparison
* Streamlit Web Application
* NLP-Based Skill Extraction
* Industry-Specific ATS Analysis

## Applications

* Job Seekers
* College Students
* Fresh Graduates
* Recruiters
* Career Guidance Platforms

## Author

Yashwanth S 

