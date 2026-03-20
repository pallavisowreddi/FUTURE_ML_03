# 📄 Resume / Candidate Screening System
**Future Interns | Machine Learning Track | Task 03 | FUTURE_ML_03**

## 📌 About This Project
Built a machine learning system to automatically screen and rank
job candidates based on a given job role using NLP techniques.
The goal is to help hiring teams shortlist candidates faster,
match skills with job requirements, and identify skill gaps
using data-driven scoring.

## 🛠️ Tools & Technologies
- Python
- Google Colab
- spaCy
- Pandas & NumPy
- Scikit-learn
- Matplotlib & Seaborn

## 📁 Dataset
- **Name:** Job Description Dataset
- **Source:** Kaggle (ravindrasinghrana)
- **Link:** https://www.kaggle.com/datasets/ravindrasinghrana/job-description-dataset

## ✅ Key Features Implemented

### 1. Data Cleaning
- Loaded real job description data
- Removed HTML tags, URLs & special characters
- Normalized and lowercased all text

### 2. Skill Extraction
- Built a domain-specific skill vocabulary
- Extracted matching skills from each job profile
- Identified required skills from reference job description

### 3. Scoring System
- **TF-IDF Vectorization** — converted text to numerical vectors
- **Cosine Similarity** — measured relevance between profiles and JD
- **Weighted Skill Scoring** — critical skills ranked higher

### 4. Ranking & Labeling
- Combined score formula:
```
Final Score = 50% Text Similarity
            + 30% Skill Match %
            + 20% Weighted Skill Score
```
- Candidates labeled as ✅ Shortlisted / 🟡 Maybe / ❌ Rejected

### 5. Skill Gap Analysis
- Identified skills present in JD but missing in candidate profile
- Helps recruiters give targeted feedback to candidates

### 6. Visualizations
- Top 10 Candidates Bar Chart
- Similarity vs Skill Match Scatter Plot
- Score Distribution Histogram
- Score Breakdown Chart (Similarity vs Skill Match vs Final Score)

## 📊 Sample Output

| Metric | Value |
|--------|-------|
| Total Candidates Screened | Based on selected role |
| Scoring Method | TF-IDF + Cosine Similarity |
| Best Model Label | Shortlisted (Score ≥ 60) |

## 💡 Business Insights
- Recruiters can shortlist top candidates in seconds instead of hours
- Skill gap report helps HR give structured feedback
- Weighted scoring ensures critical skills are prioritized
- System can be reused for any job role by changing the target title-

## 📸 Output Screenshots
All output screenshots are included in this repository.

## 🔗 Links
- 📓 Google Colab Notebook:https://colab.research.google.com/drive/15kWUhezQEUubqDEQQs9t37hFexanCpjh#scrollTo=bppftu1lPDLQ
- 💼 LinkedIn Post: [Add your LinkedIn post link here]

## 👤 Author
- **Internship:** Future Interns
- **Track:** Machine Learning
- **Task:** 03 — Resume / Candidate Screening System
