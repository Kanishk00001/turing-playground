# turing-playground

# Tensionflow - Intrusion Detection System (IDS)

## Weekend of Code 9.0 - Turing's Playground

### Team: Tensionflow

#### Team Members:
- **Vatsal Kumar** (20232057, Chemical Engineering) - [GitHub: krVatsal](https://github.com/krVatsal) *(Leader)*
- **Abhijit Saha** (20236004, ECM) - [GitHub: abhigit-saha](https://github.com/abhigit-saha)
- **Kanishk Agrawal** (20233526, CSE) - [GitHub: Kanishk00001](https://github.com/Kanishk00001)
- **Rishabh Kumar Pandey** (20232041, Chemical Engineering) - [GitHub: rishabhkrpandey](https://github.com/rishabhkrpandey)

---

## Problem Statement

**Problem Statement ID:** M-03  
**Objective:** Design a machine learning-based Intrusion Detection System (IDS) that accurately classifies network traffic and detects different types of cyber-attacks using the **NSL-KDD dataset**.

---

## Project Plan

### Phase 1: Basic Analysis

#### **Objective:** Gain insights into the NSL-KDD dataset and use simple machine learning models for intrusion detection.

- **Data Understanding:**
  - Load the dataset and analyze its structure.
  - Identify different network traffic classes (normal vs. attack types).
- **Data Preprocessing:**
  - Handle missing values.
  - Convert categorical data into numerical format using one-hot encoding.
  - Normalize data for better model performance.
- **Model Development:**
  - Split data into training and testing sets.
  - Train basic ML models such as **Decision Trees** and **Logistic Regression**.
- **Visualization:**
  - Use **Matplotlib** and **Seaborn** to visualize data.
  - Identify feature relationships and patterns.
- **Evaluation:**
  - Assess performance using **accuracy**.
  - Generate confusion matrices to analyze classification results.

---

### Phase 2: Advanced Analysis

#### **Objective:** Enhance the Intrusion Detection System by implementing more advanced techniques and improving accuracy.

- **Feature Engineering:**
  - Select the most important features to improve detection.
  - Create new features to capture hidden patterns.
- **Handling Class Imbalance:**
  - Apply **oversampling** or **undersampling** to balance attack types.
- **Advanced Model Development:**
  - Implement **Support Vector Machines (SVM)** for better accuracy.
  - Experiment with **ensemble methods** to boost performance.
- **Hyperparameter Tuning:**
  - Optimize model parameters using **Optuna**.
- **Evaluation:**
  - Use **cross-validation** to improve generalization.
  - Evaluate using **precision, recall, and F1-score**.
- **Deployment:**
  - Develop a simple **Django-based user interface**.
  - Test IDS in a controlled environment for real-time detection.

---

## Tech Stack & Libraries Used

- **Python**
- **Pandas**
- **NumPy**
- **Scikit-learn**
- **Matplotlib**
- **Seaborn**
- **Optuna** *(for hyperparameter tuning)*

---

## Project Highlights

✔️ **Structured approach** with progressive learning from basic to advanced techniques.  
✔️ **Hyperparameter tuning** using **Optuna** for best algorithm selection. 

---


## Future Scope

🚀 **Deep Learning Approaches:** Experimenting with CNNs & RNNs.  
🚀 **Real-time Implementation:** Deploying IDS on actual network traffic.  
🚀 **Integration with Cloud Services:** Making the IDS scalable.  

---

### 📌 **Contributors**
Feel free to contribute by submitting issues or pull requests!

---

