# 📦 Amazon Last-Mile Delivery Optimization

An End-to-End Data Analytics and Machine Learning project designed to predict and prevent first-attempt delivery failures, potentially saving operations costs.

---

## 📌 Business Problem
Amazon incurs significant operational costs, customer refunds, and delivery associate (DA) re-attempt expenses due to failed first-attempt deliveries. Currently, operations teams only receive failure data **after** the shift. 

**The Solution:** This project acts as an **Early Warning System (EWS)** to flag high-risk shipments *before* the dispatch vehicle leaves the delivery station.

---

## 🛠️ Tech Stack & Tools
* **Data Generation & Modeling:** Python (Pandas, Scikit-Learn)
* **Database & Analysis:** SQL (pandasql)
* **Environment:** Google Colab, GitHub

---



### Power BI dashboard 



<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/8b65a216-c51e-4132-bcd1-0cb721e9482f" />


## 🚀 Project Workflow

### 1. Data Engineering & Simulation
Since Amazon's internal logistics data is proprietary, I utilized a simulated relational logistics dataset featuring real-world biases:
* Higher failure/critical rates based on product importance and low customer ratings.
* Structured features to mimic Amazon's backend.

### 2. SQL Analysis (Failure Pattern Mining)
Developed queries using `pandasql` directly in the notebook to pinpoint risk factors, analyze order distributions, and flag critical shipments.

### 3. Machine Learning (The Predictive Engine)
Built a classification pipeline to assign a failure/critical probability score to each shipment, ensuring we flag maximum potential failures pre-dispatch.

---

## 📈 Projected Business Impact
> "By flagging high-risk shipments pre-dispatch and proactively re-assigning slots/drivers, this model estimates a significant reduction in failed deliveries, leading to thousands of dollars in monthly savings per station."
