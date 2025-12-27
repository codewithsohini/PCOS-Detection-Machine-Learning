# PCOS Detection using Machine Learning 🩺

This project aims to assist healthcare professionals in detecting Polycystic Ovary Syndrome (PCOS) using clinical parameters such as BMI, Hormone levels, and Follicle counts.

## 📊 Project Overview
- **Goal:** Binary classification of PCOS diagnosis.
- **Dataset:** 1,000 clinical records including age, BMI, and hormonal markers.
- **Algorithms Used:** Logistic Regression, Random Forest.
- **Key Outcome:** Achieved 100% accuracy with Random Forest, optimized via RandomizedSearchCV.

- ## 🤖 Modeling Strategy
In this project, I performed a comparative analysis between two distinct modeling approaches:

1. **Baseline Model (Logistic Regression):** Implemented to test the linear separability of the PCOS data. While it performed well (~88% accuracy), it suggested that a more complex model was needed to capture all diagnostic nuances.
2. **Optimized Model (Random Forest):** Used as an ensemble learner to handle non-linear feature interactions. I further optimized this model using `RandomizedSearchCV` to fine-tune hyperparameters like `max_depth` and `n_estimators`.

**Conclusion:** The Random Forest model emerged as the superior choice, providing perfect classification across all metrics on the test set.

## 📈 Key Insights
- **Top Predictors:** Testosterone levels and Antral Follicle Count were identified as the most significant clinical markers.
- **EDA:** Correlation analysis showed a strong link between BMI and menstrual irregularity in diagnosed cases.

## 🛠️ How to Use
1. Clone the repo: `git clone https://github.com/codewithsohini/PCOS-Detection-Machine-Learning.git`
2. Install dependencies: `pip install pandas scikit-learn seaborn matplotlib`
3. Run the notebook: `PCOS_Analysis.ipynb`

## 📁 Repository Structure
- `pcos_dataset.csv`: Raw clinical data.
- `PCOS_Analysis.ipynb`: Full EDA, preprocessing, and modeling code.
