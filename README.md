# Predictive-Modeling-of-Wound-Healing
# Predictive Modeling of Wound Healing Using Lactate Monitoring

## 1. Motivating Application
Diabetic foot ulcers (DFUs) are a major health concern, often leading to infections and amputations.  
This project develops predictive models using **real-time lactate monitoring** to assess wound healing.  
By analyzing wound closure and lactate levels in both healthy and diabetic mice, the goal is to enable early detection of healing complications and optimize treatment strategies.

---

## 2. Data Sets

- **Initial Data**  
  - Time series readings from **10 healthy** and **10 diabetic** mice.  
  - Features: lactate level changes and wound closure percentage over time.  

- **Anticipated Data**  
  - Additional biomarkers (pH, uric acid, temperature).  
  - These factors are critical for accurate wound healing assessment:  
    - pH (4–6) promotes healing.  
    - Stable temperature improves blood flow and enzyme activity.  
    - Uric acid aids tissue repair.  

---

## 3. Data Cleaning & Preparation

- **Initial**  
  - Converted Excel files into pandas DataFrames.  
  - Reshaped and reformatted rows/columns for analysis.  
  - Interpolated missing wound closure values.  

- **Anticipated**  
  - Possible restructuring to match model input requirements.  
  - No major data cleaning expected.  

---

## 4. Methods & Algorithms

- **Initial**  
  - Python-based exploratory analysis.  
  - Calculated mean & standard deviation of lactate/wound closure.  
  - Visualized trends for individual mice + aggregate plots comparing healthy vs diabetic groups.  

- **Anticipated**  
  - Neural network model to predict wound closure percentage from lactate levels.  

---

## 5. Project Goals

- **Short-Term**  
  - Build and evaluate models predicting lactate levels from time series data.  
  - Compare different modeling approaches for accuracy.  

- **Long-Term**  
  - Identify features from lactate (and additional biomarkers) most predictive of wound healing.  
  - Balance model accuracy, complexity, and interpretability for clinical relevance.  

---

## 6. Challenges

- **Current**  
  - Improving neural network accuracy (tuning neurons, layers).  
  - Incorporating wound closure alongside lactate levels.  

- **Anticipated**  
  - Limited dataset size: only 10 mice per group with wound closure recorded at 3 time points.  
  - Risk of overfitting due to small sample size.  

---

## 7. Tools & Environments

- **Python**  
  - PyTorch, NumPy, pandas, scikit-learn (ML + neural networks).  

- **R**  
  - Statistical analysis and visualization.  

---

## 8. Contributors
- Project completed under the mentorship of Dr. Mansoor Haider, Dr. Ashley Brown, and Amay J. Bandodkar.  
- Group mentors: Nooshin Zandi, Nivesh Sharma.  


---
