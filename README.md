# 🎯 AI-Powered Resume Ranker  
An intelligent resume-ranking system built with Python & NLP.

---

## 🔍 Overview  
In today’s fast-moving hiring world, recruiters are often swamped with resumes.  
This project leverages AI and NLP to **automatically evaluate and rank candidate resumes** — enabling faster, fairer, and data-driven hiring decisions.  
The Resume Ranker ingests resumes, processes them, extracts meaningful information, computes a ranking score, and outputs a ranked list of candidates with insights.

---

## 💡 Motivation  
- Manual resume screening is time-consuming and prone to inconsistency.  
- An AI-powered approach can help reduce unconscious bias, improve efficiency, and ensure top talent doesn’t slip through the cracks.  
- As part of my BE in CSE (AIML) and my full-stack/AI project experience, I wanted to build something practical that bridges NLP with real-world hiring tools.

---

## ✨ Features  
- ✅ Extracts structured data from raw resumes (skills, experience, education, keywords)  
- ✅ Applies NLP techniques (tokenization, keyword matching, embeddings) to build candidate profiles  
- ✅ Computes a ranking score based on customizable weights (skills match, experience depth, education relevance)  
- ✅ Outputs a ranked list of resumes with scores and highlights (why this candidate ranks higher)  
- ✅ Modular Python architecture—easy to extend and customise

---

## 🧰 Tech Stack  
- **Programming Language:** Python  
- **NLP & Data Processing:** spaCy / NLTK / Pandas (depending on modules used)  
- **UI/Interface:** (If applicable) Streamlit or Flask  
- **Storage:** CSV / JSON for resume dataset and ranking outputs  
- **Modeling:** Custom scoring logic or ML model (if applied)  
- **Deployment:** Lightweight script or web-app for recruiters

---

## 🧱 Architecture
Raw Resumes → NLP Pre-processing → Feature Extraction → Ranking Model → Ranked Output + Insights

---

- **Resume Processor:** Reads PDF/DOCX/TXT files, cleans text  
- **Feature Extractor:** Parses for skills, years of experience, education level, keywords  
- **Ranker:** Applies weighted scoring or trained model to compute final ranking  
- **Output Module:** Generates ranked list with score explanation

---

## 📥 Usage  
1. Clone the repository:  
   ```bash
   git clone https://github.com/username/AI-Powered-Resume-Ranker.git  
   cd AI-Powered-Resume-Ranker
   ```
   
2. Install dependencies:
   ```bash
   pip install -r requirements.txt  
   ```

3. Prepare your resume dataset: place your resumes (PDF/DOCX/TXT) in the designated folder or adapt the script path.

4. Configure settings: e.g., adjust weighting of skills vs experience in config or code.

5. Run the main script:
   ```bash
    streamlit run main.py
   ```

6. View the output: a ranked list of candidates with scores and summary highlights.

---

📊 Results & Demo
Example output: Candidate A (Score = 92) — matches 85% of required skills, 5+ years relevant experience, advanced degree.

Candidate B (Score = 78) — matches 70% of skills, 3 years experience, undergraduate degree.

---

##  License

This project is licensed under the **MIT License**.  
See the [LICENSE](LICENSE) file for details.
