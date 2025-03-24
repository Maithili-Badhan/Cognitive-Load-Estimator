Cognitive Load Estimator Model

📌 Overview

This project develops a Cognitive Load Estimator Model using Photoplethysmography (PPG) data sourced from Kaggle. The model analyzes PPG signals to infer cognitive load variations based on physiological patterns.

📂 Dataset

Source: Kaggle (PPG-based dataset for cognitive load analysis)

Files Used:

Annotations CSV: Contains event timestamps, sleepiness scores, and diary entries.

PPG CSV (Day 1 & Day 2): Time-series PPG signal data with Red_Signal values.

🛠️ Preprocessing

Data Cleaning:

Handled missing values and inconsistencies.

Standardized timestamps for proper synchronization.

Signal Processing:

Normalized Red_Signal values.

Applied filtering techniques to remove noise.

Feature Engineering:

Extracted statistical features (mean, variance, etc.).

Derived heart rate variability metrics.

🏗️ Model Development

Baseline Model: Implemented a simple CNN for signal classification.

Grad-CAM Analysis: Visualized feature importance.

Ensemble Models: Experimented with various architectures to improve performance.

📊 Evaluation

Compared multiple models based on accuracy, precision, recall, and F1-score.

Used Grad-CAM for interpretability analysis.

🚀 Future Enhancements

Integrate Real-Time Wearable Data: Incorporate live sensor inputs.

Expand Feature Set: Include additional physiological signals.

Optimize Model Performance: Experiment with advanced deep learning architectures.

📌 How to Use

Clone the repository.

Install dependencies (pip install -r requirements.txt).

Run preprocessing.py to prepare the data.

Train the model using train.py.

Evaluate using evaluate.py.

✉️ For questions or contributions, feel free to reach out!
