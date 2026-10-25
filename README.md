SMS Spam Classification Using Machine Learning

Project Overview
This project classifies SMS messages as **Spam** or **Ham (Legitimate)** using machine learning algorithms and TF-IDF text feature extraction.

Dataset
- **Source:** Kaggle — SMS Spam Collection Dataset
- **Records after preprocessing:** 5,169
- **Features:** SMS message text
- **Target:** Ham or Spam

Technologies Used
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- TF-IDF Vectorization
- Google Colab

Machine Learning Algorithms
1. Decision Tree
2. K-Nearest Neighbors (KNN)
3. Support Vector Machine (SVM)
4. Multinomial Naive Bayes

Results
The models were evaluated using accuracy, precision, recall, F1-score, confusion matrices, and execution time.

The best-performing original model was **SVM**, with approximately **97.97% accuracy**. In the parameter experiment, SVM with C = 10 achieved approximately **98.26% accuracy** and an **F1-score of 92.74%**.

What-If Experiment
The SVM regularization parameter C was tested at 0.1, 1, and 10 to study its effect on classification performance.

Project Files
- `.ipynb` — Complete Google Colab notebook
- `.docx` — Project report
- `model_comparison_results.csv` — Comparison of the four models
- `svm_what_if_results.csv` — SVM parameter experiment results
- `project_summary.txt` — Project summary, if included

Conclusion
Among the four original models, SVM achieved the best overall performance based on accuracy and F1-score. The parameter experiment showed that increasing C from 1 to 10 improved the observed results on the test set.

Dataset Reference
[Kaggle — SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)
