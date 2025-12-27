# PCOS Detection using Machine Learning 🩺

This project aims to assist healthcare professionals in detecting Polycystic Ovary Syndrome (PCOS) using clinical parameters such as BMI, Hormone levels, and Follicle counts.

## 📊 Project Overview
- **Goal:** Binary classification of PCOS diagnosis.
- **Dataset:** 1,000 clinical records including age, BMI, and hormonal markers.
- **Algorithms Used:** Logistic Regression, Random Forest.
- **Key Outcome:** Achieved 100% accuracy with Random Forest, optimized via RandomizedSearchCV.

## 📈 Key Insights
- **Top Predictors:** Testosterone levels and Antral Follicle Count were identified as the most significant clinical markers.
- **EDA:** Correlation analysis showed a strong link between BMI and menstrual irregularity in diagnosed cases.

## 🛠️ How to Use
1. Clone the repo: `git clone https://github.com/codewithsohini/PCOS-Detection-Machine-Learning.git`
2. Install dependencies: `pip install pandas scikit-learn seaborn matplotlib`
3. Run the notebook: `PCOS analysis.ipynb`

## 📁 Repository Structure
- `pcos_dataset.csv`: Raw clinical data.
- `PCOS analysis.ipynb`: Full EDA, preprocessing, and modeling code.
