# Power Grid Anomaly Detection using Machine Learning
This project is the result of my Master’s thesis focused on detecting anomalies in power grid infrastructures using machine learning techniques. It introduces a comprehensive methodology for identifying abnormal patterns in power consumption data — essential for early detection of faults, cyber-attacks, or equipment failures in modern smart grids.

## 📄 Thesis
You can read the full thesis here: [`Thesis_final_version.pdf`](./Thesis_final_version.pdf)

## 📊 Experiments
- 6 anomaly types simulated (spikes, zero values, noise, load drop/increase, repeats)
- Models tested: Decision Tree, Random Forest, Gradient Boosting, XGBoost, LSTM
- Metrics: Accuracy, Precision, Recall, F1-score, Confusion Matrix
- Feature Engineering: delta, lag, moving average

## 🧠 Code
Google Colab notebook: [`anomaly_detection_power_grid.ipynb`](./anomaly_detection_power_grid.ipynb)

## 📈 Results
Detailed performance results in `results/` folder.

## 💡 Technologies
- Python, Pandas, Scikit-learn, TensorFlow/Keras
- Google Colab for experiments

## 🔗 Links
- [Colab Notebook](https://colab.research.google.com/drive/1cGj50LsdC9pVx1ScBQ_mjZLill64xqLw?usp=sharing#scrollTo=EO6YIXubn6N9)
- [Excel Results Folder](https://drive.google.com/drive/folders/1O0LYpzkIX_ROIvx2EINS7L2Kamivx1YR?usp=drive_link)
