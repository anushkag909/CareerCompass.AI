# 🧭 CareerCompass AI

### An Intelligent AI Career Guidance & Resume Analysis Platform

CareerCompass AI is an AI-powered career guidance system designed to analyze resumes, extract technical skills, identify skill gaps, recommend suitable career paths, and generate personalized learning roadmaps.

The project uses Python, NLP, data processing, and machine learning techniques to provide career-related insights based on a candidate's resume.

## 🚀 Project Overview

CareerCompass AI analyzes resume data and generates insights to help candidates understand their skills, strengths, career suitability, and areas for improvement.

The system extracts information from PDF resumes and performs skill analysis, career matching, resume scoring, and learning recommendations.

## ✨ Features

- 📄 **Resume Parsing:** Extract text and information from PDF resumes.
- 👤 **Candidate Information Extraction:** Identify candidate name, email, phone number, education, projects, and certifications.
- 🛠️ **Technical Skill Extraction:** Detect technical skills using a predefined skill database.
- 📊 **Skill Gap Analysis:** Identify missing skills based on target career requirements.
- 🎯 **Career Recommendation:** Recommend suitable career roles based on detected skills.
- 📈 **Career Match Analysis:** Calculate career-match percentages for different roles.
- 📝 **Resume Score:** Evaluate resume completeness using a heuristic scoring approach.
- 💡 **Learning Recommendations:** Suggest learning resources based on identified skill gaps.
- 🗺️ **Personalized Career Roadmap:** Generate a structured learning and career preparation roadmap.
- 📊 **Resume Dashboard:** Visualize important resume metrics.
- 📂 **Batch Resume Analysis:** Analyze multiple PDF resumes in one workflow.
- 📥 **CSV Export:** Download batch analysis results.
- 📦 **ZIP Support:** Upload ZIP files containing multiple PDF resumes.

## 🧠 How It Works

1. Upload a resume in PDF format.
2. Extract text from the resume.
3. Identify candidate information.
4. Detect technical skills.
5. Extract education, projects, and certifications.
6. Compare detected skills with career requirements.
7. Identify missing skills and skill gaps.
8. Calculate career-match scores.
9. Generate career recommendations.
10. Create learning recommendations and a personalized roadmap.
11. Visualize resume metrics.
12. Export batch analysis results when multiple resumes are processed.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- spaCy
- PyMuPDF
- pdfplumber
- Regular Expressions
- Matplotlib
- Plotly
- Streamlit
- Google Colab

## 📌 Career Roles Analyzed

The project includes skill requirements for roles such as:

- Data Scientist
- Machine Learning Engineer
- AI / NLP Engineer
- Data Analyst

## 📊 Resume Analysis

The system evaluates resume information through multiple components:

- Technical skills
- Education
- Projects
- Certifications
- Professional summary
- Career-specific skill requirements

The resume score is based on resume completeness and should not be interpreted as a hiring prediction.

## 📂 Project Structure

```text
CareerCompass-AI/
│
├── CareerCompassAI.ipynb
├── README.md
└── requirements.txt
```

## ▶️ How to Run

### Google Colab

1. Open the notebook in Google Colab.
2. Run the installation and import cells.
3. Upload a PDF resume when prompted.
4. Execute the notebook cells sequentially.
5. Review the extracted information and career insights.

### Required Libraries

```bash
pip install pandas numpy scikit-learn spacy
