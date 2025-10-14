# 💌 Bounceback Donor Analytics – Optimising Ask Strategies for Long-Term Impact  

## 🌟 Highlights  
- Developed a **data-driven model** to personalise donor ask amounts and reduce disengagement risk.  
- Identified **donor churn trends** of 51–58% annually, revealing $775K in revenue at risk.  
- Built **Random Forest and Regression models** to predict donor capacity and right-size ask amounts.  
- Proposed a **behaviour-led segmentation** replacing one-size-fits-all multipliers, improving prediction accuracy by **61%**.  
- Designed **seasonal and channel-specific strategies** to balance engagement, cost, and ROI across donor cohorts.  

---

## ℹ️ Overview  
This project was developed for **World Vision Australia (WVA)** as part of **MIS779 – Business Analytics Portfolio (Capstone)** at Deakin University.  
The analysis focuses on optimising **Bounceback campaign ask strategies** to enhance donor retention, sustain long-term giving, and reduce donor fatigue.  

The team aimed to answer:  
> *How might WVA segment its donors and personalise ask amounts to maintain ongoing donations, minimise communication fatigue, and lower disengagement risk?*  

Using exploratory, predictive, and diagnostic analytics, the project produced actionable insights and predictive models to drive a shift from fixed multipliers to **personalised, behaviour-based asks**.

---

## 📈 Key Analytical Components  

### **Descriptive Analysis**  
- Tracked donation trends and seasonal peaks — strongest in **Q4 (Christmas)** and weakest in **Q1–Q3**.  
- Found donor concentration in **older (55+) “Leading Lifestyles” segments**, indicating reliance on mature, high-value supporters.  
- Identified consistent donor churn between **51–58% per year**, with revenue risk rising year-over-year.  

### **Predictive & Diagnostic Modelling**  
Two predictive models guided the campaign redesign:  

1. **Random Forest Classifier**  
   - Predicted donor gift bands: *Small (<$30), Medium ($30–60), High ($60–100)*.  
   - Key predictor: **Cumulative Average Paid**, explaining ~60% of predictive power.  
   - Achieved **71% recall accuracy** for high-band donors, validating stable giving behaviour.  

2. **Multiple Linear Regression**  
   - Estimated precise donation amounts for **personalised asks**.  
   - Introduced a **weighted average (0.6, 0.3, 0.1)** across last three donations.  
   - Reduced mean absolute error (MAE) by **61%**, aligning ask amounts more closely with real giving behaviour.  

---

## 💡 Strategic Recommendations  

### **1. Behaviour-Based Segmentation**  
Replace the current multiplier-based model with data-led segments:  
| Segment | Typical Donation | Ask A | Ask B | Ask C | Strategy |
|----------|------------------|-------|-------|-------|-----------|
| New Supporters / Non-responders | < $30 | $15 | $20 | $25 | Re-engage with small base asks |
| Growth Potential | $30–60 | $30 | $40 | $50 | Encourage frequency and loyalty |
| Mid Capacity | $60–100 | $55 | $70 | $90 | Balanced incremental approach |
| High Capacity | > $100 | 0.8× | 1.0× | 1.3× | Personalised, prediction-anchored ask |

---

### **2. Seasonal Campaign Optimisation**  
- Apply **seasonal multipliers**:  
  - 🎄 Christmas = **1.15**  
  - 🎂 Birthday = **1.00**  
  - 📚 Education = **0.95**  
- Use Christmas and EOFY campaigns for **high-value asks** and loyalty reinforcement.  

---

### **3. Channel Realignment**  
- Maintain **offline communications** for older donors (55+) who respond best to direct mail.  
- Shift younger donors (<45) to **digital-first engagement** (EDMs, chatbot reminders, app pushes).  
- Reduce DM pack costs for non-engagers and redirect savings to personalised digital outreach.  

---

### **4. Personalised Ask Logic Example**  
For a donor with past gifts of $550, $600, and $700:  
- Predicted next gift = $605  
- **Ask Ladder:**  
  - Ask A = $605 × 0.8 = $500  
  - Ask B = $605 × 1.0 = $600  
  - Ask C = $605 × 1.3 = $800  

Compared to the current multiplier model ($700, $850, $1,100), this approach prevents over-asking and improves donor comfort.  

---

## 🧩 Expected Impact  
- **15–25% reduction** in donor churn rate.  
- **Significant recovery** of ~$775K projected revenue at risk.  
- More equitable and sustainable donation practices, balancing loyalty and financial targets.  

---

## 🧰 Tools & Techniques  
- **Python (pandas, scikit-learn)** – Predictive modelling (Random Forest, Regression).  
- **Excel & Power BI** – Data cleaning, exploratory analysis, and dashboarding.  
- **Statistical Modelling** – Weighted regression, feature engineering, and validation.  
- **Behavioural Segmentation** – Based on frequency, tenure, and average paid amount.  
- **Campaign Analytics** – Seasonal uplift, response lag, and channel performance tracking.  

---

## 👤 Authors  
**Group 42 – Deakin University (MIS779 – Business Analytics Portfolio)**  
- **Ba Huy Hoang Le** – 224309594  
- **Amey Bimal Shah**  
- **Nandhini Karunakaran**  
- **Shriya Deepak Bhandare**  
- **Sreya Mangatt**  
- **Aleena Sabastian**  

---

## 📜 Acknowledgement of AI Use  
Some text drafting, grammar checks, and structure suggestions were assisted by AI tools, with all final content reviewed and edited by the authors to ensure originality, accuracy, and academic integrity.  
