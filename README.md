
# 📄 Resume Screening using Machine Learning
### AI-Powered Candidate Ranking & Automated NLP Parsing

<p align="center">
<img src="https://img.shields.io/badge/Python-3.8+-blue?style=for-the-badge&logo=python">
<img src="https://img.shields.io/badge/NLP-NLTK%20%7C%20SpaCy-green?style=for-the-badge">
<img src="https://img.shields.io/badge/ML-Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn">
<img src="https://img.shields.io/badge/Status-Optimized-brightgreen?style=for-the-badge">
<img src="https://img.shields.io/badge/Platform-Jupyter-orange?style=for-the-badge&logo=jupyter">
</p>

---

## 🌟 Overview

The recruitment process is often overwhelmed by thousands of applications, making manual review nearly impossible. This project implements an **AI-powered Resume Screening system** that leverages **Natural Language Processing (NLP)** to automate candidate evaluation. By extracting key skills, education, and experience, the system ranks candidates against specific job descriptions with high precision.



### Core Capabilities:
- **Smart Information Extraction:** Detects and classifies entities like skills, job titles, and educational degrees using Named Entity Recognition (NER).
- **Semantic Matching:** Goes beyond basic keywords by using TF-IDF and word embeddings to understand contextual relevance.
- **Scalable Processing:** Capable of handling hundreds of resumes in seconds, reducing recruiter workload significantly.
- **Objective Scoring:** Minimizes human bias by providing a data-driven score based on profile-to-job alignment.

---

## 🧠 Tech Stack

| Category | Tools |
| :--- | :--- |
| **Language** | Python 3.8+ |
| **NLP Frameworks** | NLTK, SpaCy, Transformers (BERT) |
| **ML Algorithms** | Random Forest, Logistic Regression, SVC |
| **Data Handling** | Pandas, NumPy |
| **Visualization** | Matplotlib, Seaborn |

---

## 📁 Project Structure

```bash
Resume_Screening/
├── data/
│   └── resume_dataset.csv     # Kaggle/Custom dataset for training
├── src/
│   └── resumeScreening.ipynb  # Main NLP pipeline & ML training
├── assets/
│   └── feature_importance.png # Key skills driving the model
├── requirements.txt           # Environment dependencies
└── README.md                  # Project documentation

```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone [https://github.com/G-Narendra/Resume_Screening.git](https://github.com/G-Narendra/Resume_Screening.git)
cd Resume_Screening

```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt

```

### 3️⃣ Start the Analysis

```bash
jupyter notebook resumeScreening.ipynb

```

---

## 📈 Methodology & Performance

The project follows a rigorous text-processing pipeline:

1. **Cleaning:** Removing special characters, stopwords, and URLs.
2. **Vectorization:** Converting text into numerical vectors using **TF-IDF** (Term Frequency-Inverse Document Frequency).
3. **Classification:** Segmenting resumes into categories (e.g., Data Science, Web Dev, HR) to ensure domain-specific ranking.

### Model Metrics:

The system benchmarks several classifiers to ensure maximum accuracy:

* **Random Forest:** Best for capturing non-linear relationships in skill sets.
* **SVM:** High precision in high-dimensional text data.
* **Evaluation:** Tracked via **F1-Score** and **Precision** to ensure no top-tier talent is missed.

---

## 👨‍💻 Author

**Narendra (G‑Narendra)** AI | ML | Python | Full Stack | GenAI Enthusiast

📧 [Email Me](mailto:narendragandikota2540@gmail.com) | 💼 [LinkedIn](https://linkedin.com/in/g-narendra/) | 👨‍💻 [GitHub](https://github.com/G-Narendra)

🌐 [Portfolio](https://g-narendra-portfolio.lovable.app/)

---

<p align="center">⭐ If you find this project useful, feel free to give it a star! 🚀</p>
