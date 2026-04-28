
## Credit Card Fraud Detection System 

### Overview

This project presents a **hybrid credit card fraud detection system** that combines **Machine Learning (ML)** models with **SMS-based user verification** to improve fraud detection in the Sri Lankan financial environment.

With the rapid growth of digital payments and e-commerce in Sri Lanka, traditional rule-based fraud detection systems are no longer sufficient. This project addresses that gap by introducing a **data-driven and user-interactive approach**.

---

### Key Objectives

* Detect fraudulent credit card transactions using ML models
* Compare performance between **global** and **Sri Lankan datasets**
* Handle **class imbalance issues** in fraud detection
* Enhance security with **SMS-based transaction verification**
* Provide a **realistic fraud prevention workflow**

---

### Datasets Used

* **Dataset 1 (Global Dataset)**

  * 2,512 transactions with 16 features
  * Highly imbalanced (very few fraud cases)

* **Dataset 2 (Sri Lanka Local Dataset)**

  * 860 transactions
  * More balanced and context-relevant
  * Includes financial attributes like GrossAmount, DiscountAmount, NetAmount

---

### ⚙️ Technologies & Tools

* Python
* Scikit-learn
* Pandas, NumPy
* Isolation Forest (Anomaly Detection)
* Logistic Regression
* Random Forest
* Support Vector Machine (SVM)

---

### Models Implemented

* **Isolation Forest** (Unsupervised anomaly detection)
* **Logistic Regression**
* **Random Forest** 
* **Support Vector Machine (SVM)**

---

### System Workflow

1. Transaction occurs
2. User receives SMS verification

   * Reply **"NO" → Transaction rejected immediately**
   * Reply **"YES" → Sent to ML model**
3. ML model classifies transaction as:

   * Approved
   * Declined

---

### Key Results

#### Dataset 1 (Global)

* Accuracy: **0.88**


#### Dataset 2 (Sri Lanka)

* Random Forest Accuracy: **0.88**


---

### 💡 Key Insights


* Random Forest performs best in balanced datasets
* SMS verification acts as a **safety layer**, reducing missed fraud cases



