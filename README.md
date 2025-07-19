# Resume-Checker!
Here’s a ready-to-copy description for your `README.md` on GitHub:

---

## 🚀 Resume Checker (ATS-Based Resume Analyzer)

This project is a resume analysis tool that evaluates how well a resume matches a given job description (JD). It uses OCR, NLP, and a predefined skill matrix to score the resume against ATS (Applicant Tracking System) criteria. Built using Python, Gradio, and Tesseract OCR, it provides both a visual ATS match score and role recommendations.

### 🔍 Features

* 📝 **Text Extraction** from PDF resumes using `pdf2image` and `pytesseract`
* 💼 **Keyword Extraction** from job descriptions
* 📊 **Skill Matching** against 10 popular tech job roles
* 🎯 **ATS Score Calculation** and role match percentage
* 📈 **Pie Chart Visualization** of the ATS score
* 🌐 **Gradio Web Interface** for easy use
* ✅ Clear recommendations for improving resume relevance

### 🛠️ Roles Supported

* AI/ML Intern
* Data Analyst
* Web Developer
* Backend Developer
* Cloud Engineer
* DevOps Engineer
* Cybersecurity Analyst
* Data Scientist
* Business Analyst
* Full Stack Developer

### ⚙️ Technologies Used

* Python
* Gradio
* Tesseract OCR
* PyMuPDF (`fitz`)
* NLTK
* Matplotlib
* PDF2Image

### 📦 Installation

```bash
!apt-get install -y poppler-utils
!pip install gradio==3.50.2 pdf2image pytesseract nltk matplotlib PyMuPDF
```

---

Let me know if you want a shorter version or one that includes setup and usage steps too.

