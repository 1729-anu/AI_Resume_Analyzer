# 🧠 AI Resume Analyzer

A smart resume parsing and analytics tool using Natural Language Processing (NLP) to extract structured information, recommend improvements, and provide visual analytics for applicants and recruiters.

---

## 💡 Features

### 👤 Applicant Panel

- Upload a resume (PDF) and receive:
  - Extracted personal information
  - Identified skills and keyword clusters
  - Recommended additional skills
  - Predicted job roles and matching scores
  - Suggested courses and certifications
  - Resume tips and improvement ideas
  - Interview guidance video recommendations
  - Overall resume score

### 🛠 Admin Panel

- View structured data from all resumes
- Export resume data to CSV
- Access all uploaded resumes in one place
- View user analytics with pie charts for:
  - Resume scores
  - Predicted roles
  - Experience levels
  - Locations (City, State, Country)
  - Feedback ratings
- Review user feedback and comments

### 📝 Feedback System

- 1–5 star ratings
- Comment submission
- Feedback analytics dashboard

---

## 🧰 Tech Stack

| Layer        | Technologies                     |
|--------------|----------------------------------|
| Frontend     | Streamlit                        |
| Backend      | Python, NLP (spaCy, pyresparser) |
| Database     | MySQL                            |
| Visualization| Matplotlib, Streamlit Charts     |

---

## 📦 Installation & Setup

### Requirements
- Python 3.9.12
- MySQL
- Visual Studio Code
- Visual Studio Build Tools (for some packages)

### Steps

```bash
# Clone the repo
git clone https://github.com/deepakpadhi986/AI-Resume-Analyzer.git
cd AI-Resume-Analyzer

# Set up virtual environment
python -m venv venvapp
venvapp\Scripts\activate  # Use source venvapp/bin/activate for Linux/macOS

# Install dependencies
cd App
pip install -r requirements.txt

# Download NLP model
python -m spacy download en_core_web_sm
