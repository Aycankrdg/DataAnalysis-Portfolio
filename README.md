# Data Analysis Portfolio — Healthcare Focus

**Aycan Karadağ** — Health Management Student | Data-driven healthcare analytics  
📧 aycannzl2606@hotmail.com  

---

## About
This repository contains a selected portfolio of healthcare data analysis reports completed as part of coursework and independent projects. The focus areas are digital health communication, hospital cost management, patient analytics using machine learning, and epidemiological modeling.  

---

## Contents
- `Reports/` — Full project reports (PDF / DOCX)  
- `Visuals/` — Figures and key charts extracted from reports  
- `README.md` — This overview and quick links to each project  

---

## Projects (short summaries)

### 1) COVID-19 Vaccine Discourse Analysis (Twitter)
**File:** `Reports/COVID19_Twitter_Analysis.pdf`  
**Type:** Text mining, Sentiment analysis, Topic modeling, Network analysis  
**Tools (reported):** R (tidyverse, tm, topicmodels, igraph), sentiment lexicons  
**Summary:** Analysis of ~222,450 vaccination-related tweets (Dec 2020) to identify dominant themes (logistics/access), sentiment distribution (slightly positive average), and brand/regional patterns (Covaxin prominence). Key findings emphasize access/logistics as primary public concerns and phase-specific communication needs.  

---

### 2) Strategic Healthcare Cost Management
**File:** `Reports/Strategic_Healthcare_Cost_Management.docx`  
**Type:** Operational analytics, cost drivers, predictive modeling  
**Tools (reported):** R (tidyverse, randomForest, rpart), clustering, regression  
**Summary:** Integrated analysis across finance, inventory, patient, and staffing datasets. Identified overtime and staffing costs as major drivers; proposed operational levers for cost optimization and predictive alerts for deteriorating performance.  

---

### 3) Patient Segmentation & Test Result Prediction (ML)
**File:** `Reports/Patient_Segmentation_ML.docx`  
**Type:** Clustering (K-means), Decision Tree, Random Forest  
**Tools (reported):** R (caret, randomForest)  
**Summary:** Patient segmentation on 55,500 records (sampled n=5,000) produced three clinically meaningful clusters (low-cost short-stay, high-cost medium-stay, low-cost extended-stay). Predictive models for test results achieved ~34% accuracy (limited by administrative-only features); billing amount, age, and length of stay were most informative.  

---

### 4) The Impact of Demographic Factors on Diabetes Prevalence (BRFSS 2015)
**File:** `Reports/HealthResearchReport.pdf`  
**Type:** Epidemiological analysis, Logistic regression, Chi-square tests  
**Tools (reported):** R (tidyverse, ggplot2, dplyr)  
**Summary:** Analysis of 250,000+ U.S. adults from the 2015 BRFSS dataset exploring how **age, gender, income, and education** affect diabetes prevalence. Significant findings include:  
- Diabetes risk increases steeply after age 50.  
- Lower education and income are linked to higher prevalence.  
- Males show slightly higher rates than females.  
Policy implications highlight the need for **targeted preventive strategies** addressing socio-economic disparities.  

---

### 5) Which Customer Action Speaks Loudest? (Marketing Analytics Project)
**File:** `Reports/Customer_Purchase_Predictors.docx`  
**Type:** Predictive modeling, Logistic regression, Random forest  
**Tools (reported):** R (caret, randomForest, pROC)  
**Summary:** Data-driven analysis of marketing campaign responses (n=20) to identify the best predictors of customer purchase decisions.  
- **Top predictors:** Age and product page visits.  
- **Model performance:** Random Forest (AUC=1.0, Accuracy=83.3%) > Logistic Regression (AUC=0.67).  
Recommendations:  
- Develop **age-segmented marketing strategies**.  
- Prioritize **product page optimization** to increase conversions.  
- Use **location-based targeting** for high-performing regions (Sydney, Perth).  

---

### 6) The Efficacy of Body Circumference Measurements in Predicting Body Fat Percentage
**File:** `Reports/Body_Circumference_Prediction.docx`  
**Type:** Correlation & Regression Analysis (Anthropometric study)  
**Tools (reported):** R (base, stats, ggplot2)  
**Summary:** Investigated the relationship between **body circumference measurements** and **body fat percentage** in adult males.  
- **Strongest predictor:** Abdominal circumference (r = 0.813, R² ≈ 0.64).  
- Regression equation: *Body Fat = 1.186 - 0.00141 × Abdomen*.  
Findings suggest abdominal circumference is a **low-cost, reliable proxy** for adiposity and can support **public health screening and obesity prevention** initiatives.  

---

## Notes on code and datasets
- These reports were created as part of coursework; original analysis scripts/datasets used during the course are **not included** here.  
- If code becomes available later, it will be uploaded to the corresponding folder (e.g., `code/`), and links will be added here.  
- All data used are either publicly available datasets (e.g., BRFSS, Kaggle) or provided in course context; any proprietary or sensitive data have been removed.  

---

## How to read these reports
- Open the corresponding file under `Reports/` (PDF/DOCX).  
- For quick visual highlights, check `Visuals/` for selected figures and charts.  

---

## Skills & Tools
R, tidyverse, ggplot2, tm/text mining, topicmodels (LDA), sentiment analysis, igraph/network analysis, clustering, decision tree, random forest, basic data engineering and reporting.  

---

## Contact
Aycan Karadağ — aycannzl2606@hotmail.com  
LinkedIn: [https://www.linkedin.com/in/aycan-karada%C4%9F/]  

---

## License
This repository contains academic course work. For reuse or collaboration inquiries, please contact the author.
