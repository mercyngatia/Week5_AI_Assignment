# AI Workflow Development - Student & Healthcare Case Studies

This repository contains the practical implementation and reflections for our AI Development Workflow assignment. It demonstrates how machine learning models can be built, evaluated, optimized, and ethically reflected on within real-world educational and healthcare scenarios.

The content covers model development, critical thinking on ethics & bias, and workflow reflection - showing how AI moves from idea to model to deployment to continuous monitoring.

---

## Part 1 - Student Dropout Prediction

Built a Gradient Boosting Classifier using academic performance, study habits, and demographic data  

**Key features:** Grades, study time, absences, failures, family support  
**Main objective:** Identify at-risk students within first 4 weeks for early intervention  
**Primary KPI:** Precision@Top-100 (correctly identifying dropouts among 100 highest-risk predictions)  
**Stakeholders:** Students, academic advisors, university administration  

---

## Part 2 - Hospital Readmission Prediction

Developed a Logistic Regression model with L1 regularization for interpretability  

**Key features:** Clinical metrics (blood pressure, cholesterol, BMI), medication count, length of stay  
**Main objective:** Predict patients at risk of readmission within 30 days  
**Primary KPI:** Recall (targeting 75% to minimize missed high-risk patients)  
**Ethical focus:** Reduce algorithmic bias across patient demographics + ensure clinical interpretability  

---

## Part 3 - Critical Thinking (Ethics & Trade-offs)

### Ethics & Bias
**Identified risks:** Biased training data could lead to unfair predictions for certain student/patient groups  
**Proposed solution:** Fairness audits - checking model performance across different demographics  
**Impact:** Prevents either missing at-risk individuals or unnecessarily flagging healthy ones  

### Trade-offs
**Interpretability vs Accuracy:** Chose interpretable models (Logistic Regression) over "black box" alternatives for clinical/educational trust  
**Resource constraints:** Selected computationally efficient models suitable for institutional resource limitations  
**Real-world priority:** Understandable predictions are more valuable than marginal accuracy gains in high-stakes environments  

---

## Part 4 - Reflection & Workflow Diagram

### Reflection
**Most challenging part:** Data preprocessing and cleaning - handling real-world data inconsistencies like string conversions and complex feature engineering  
**Reasons:** Unexpected data types, clinical format complexities (blood pressure), and the critical need for accurate data validation  
**With more time/resources:** Implement advanced bias detection, create model ensembles, build web interfaces, and add long-term performance monitoring  

---

### AI Development Workflow

Business Understanding -> Data Collection -> Data Preprocessing -> Exploratory Analysis
|
Feature Engineering -> Model Selection -> Model Training -> Evaluation & Metrics
|
Bias Assessment -> Deployment -> Monitoring -> Iteration/Feedback Loop

---
Contributors
Name	GitHub
Your Name: Mercy Ngatia	               Your GitHub:https://github.com/mercyngatia/Week5_AI_Assignment.git

This repository demonstrates our ability to:

- Design, train, and evaluate ML models for real-world problems  
- Apply critical thinking around ethics, bias, and deployment constraints  
- Document and reflect on the AI workflow end-to-end across multiple domains  
- Balance technical optimization with practical implementation considerations
