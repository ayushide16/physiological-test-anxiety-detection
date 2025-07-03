# StressSense: Real-time Stress Detection using Wearables & Machine Learning

**98%+ Accuracy & F1 Score** | **Empatica EmbracePlus**

StressSense is a research-driven project focused on **real-time stress detection** using physiological signals like **Galvanic Skin Response (GSR)** and **Heart Rate Variability (HRV)**. It evaluates the short-term effectiveness of **guided deep breathing** and **Indian classical Raga Bhairavi music** in reducing exam-induced anxiety among engineering students.

## Project Highlights

- **60 engineering students** tested under controlled stress using the **Montreal Imaging Stress Task (MIST)**
- Statistical validation using **Friedman, Wilcoxon, and Kruskal-Wallis** tests
- Physiological data collected via **Empatica EmbracePlus** wearable sensors
- ML Models used: **Random Forest, XGBoost, Decision Tree, SVM, Logistic Regression, KNN**
- **98.1% Accuracy**, **F1 Score > 0.98**, **ROC AUC > 0.96** on binary stress classification
- Currently exploring **Contrastive Learning** for representation learning on biosignals


## Methods Used

- **Physiological Signals:** GSR (EDA), HRV (BVP-derived)
- **Sensors:** Empatica EmbracePlus
- **Statistical Tests:** Shapiro-Wilk, Wilcoxon Signed-Rank, Kruskal-Wallis, Friedman
- **ML Techniques:** Supervised classifiers with cost-sensitive learning, cross-validation, and ROC analysis
- **Ongoing Work:** Contrastive learning for low-labeled, high-dimensional biosignal datasets

## Results Summary

| Model            | Accuracy | F1 Score | ROC AUC |
|------------------|----------|----------|---------|
| Random Forest    | 98.1%    | 0.98     | 0.99    |
| XGBoost          | 98.1%    | 0.98     | 0.98    |
| Decision Tree    | 98.1%    | 0.98     | 0.96    |
| SVM (RBF)        | 96.8%    | 0.97     | 0.99    |
| Logistic Reg.    | 91.1%    | 0.91     | 0.92    |

