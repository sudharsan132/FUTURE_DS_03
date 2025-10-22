# FUTURE_DS_03
# 🎓 FI_Task_03 – Student Satisfaction Survey Analysis (Python Project)

📅 **Date:** October 15, 2025  
👤 **Author:** S. Sudharsan  

This project analyzes **student satisfaction survey data** to evaluate teaching effectiveness, mentorship quality, and overall academic experience.  
Using Python-based data analysis and visualization, the project identifies **key strengths** and **areas for improvement** in institutional performance.

---

## 📘 Project Overview

The objective of this project is to gain insights into student feedback by examining survey responses related to faculty performance, engagement, and satisfaction levels.

### Key Goals:
- Evaluate average ratings for various survey questions  
- Conduct **sentiment analysis** on student feedback  
- Visualize **rating distributions** and **feedback trends**  
- Identify low-performing and high-performing areas  

---

## 🧠 Methodology

The analysis follows these major steps:

1. **Data Import & Exploration**  
   - Load the dataset (`Student_Satisfaction_Survey.csv`) using `pandas`  
   - Inspect structure, missing values, and data types  

2. **Data Preprocessing**  
   - Convert average ratings from text format to numeric values  
   - Extract rating columns (`Weightage 1–5`) for analysis  

3. **Exploratory Data Analysis (EDA)**  
   - Plot rating distributions and boxplots  
   - Generate heatmaps to find correlations between rating categories  

4. **Sentiment Analysis**  
   - Use **NLTK’s VADER** sentiment analyzer to classify feedback as  
     _Positive_, _Negative_, or _Neutral_  
   - Visualize sentiment balance with bar and pie charts  

5. **Text Visualization**  
   - Generate a **Word Cloud** of common words in feedback comments  
   - Highlight recurring themes and topics mentioned by students  

6. **Insight Extraction**  
   - Identify **low-rated questions** for improvement  
   - Highlight **positive sentiment areas** (>60% positivity)  
   - Summarize overall satisfaction metrics  

---

## 🧰 Tools & Libraries Used

| Purpose | Library |
|----------|----------|
| Data Handling | `pandas` |
| Visualization | `matplotlib`, `seaborn` |
| Text Analysis | `nltk`, `wordcloud`, `textblob` |
| Sentiment Analysis | `VADER` (NLTK) |

---

## 📊 Key Insights

- Most feedback leaned **positive**, showing general satisfaction with teaching and mentoring.  
- A few areas, such as **mentorship follow-up** and **ICT tool usage**, received **lower ratings**, indicating opportunities for improvement.  
- Word cloud and sentiment charts revealed focus on *communication*, *engagement*, and *preparation* as top positive themes.

---

## 📈 Visualizations Generated

- Distribution of Average Ratings  
- Sentiment Distribution (Pie Chart & Bar Chart)  
- Correlation Heatmap of Rating Categories  
- Word Cloud of Student Feedback  
- Average Rating per Question (Bar Graph)  
- Boxplot of Rating Spread  

---

## 💾 Output Summary

- Positive sentiment percentage per question  
- Low-scoring survey items (below average rating 3.5)  
- Exported summary tables for further review  

---

## 🎯 Learning Outcomes

- Strengthened skills in **data analysis & preprocessing** with pandas  
- Improved proficiency in **text sentiment analysis** using NLP tools  
- Learned how to **translate survey data into actionable insights**  
- Enhanced data storytelling through **visualization techniques**

---

## 📎 How to Run the Project

1. Clone this repository:
   ```bash
   git clone https://github.com/YourUsername/PowerBI-Projects.git
   cd FI_Task_03_Student_Satisfaction_Survey
