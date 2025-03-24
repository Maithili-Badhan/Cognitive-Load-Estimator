# Cognitive Load Estimator Model

## 📌 Overview
This project focuses on estimating cognitive load using PPG (Photoplethysmogram) signals from a dataset sourced from Kaggle. The model analyzes variations in PPG signals to assess the cognitive state of individuals.

## 📂 Dataset
- **Source:** Kaggle
- **Components:**
  - **Annotations CSV:** Contains event timestamps, self-reported sleepiness scores, and diary entries.
  - **PPG CSV (Day 1 & Day 2):** Includes time-series PPG signals (Red Signal values).

## 🛠️ Implementation Steps
1. **Preprocessing:**
   - Clean and structure the dataset.
   - Normalize PPG signals.
   - Handle missing values if any.
2. **Feature Extraction:**
   - Compute heart rate variability (HRV).
   - Extract time-domain and frequency-domain features from PPG signals.
3. **Model Training:**
   - Train a machine learning model (e.g., SVM, Random Forest, or Neural Network) to classify cognitive load states.
4. **Evaluation:**
   - Assess model performance using metrics like accuracy, precision, recall, and F1-score.
5. **Visualization:**
   - Plot PPG signal variations.
   - Compare cognitive load levels based on extracted features.

## 🚀 Usage
### Requirements
Ensure you have the following dependencies installed:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```
### Running the Model
```bash
python cognitive_load_estimator.py
```

## 📊 Results & Findings
- The model successfully differentiates cognitive load states using PPG signals.
- HRV features play a key role in assessing cognitive load.
- Future work includes integrating real-time wearable data for enhanced accuracy.

## 📜 License
This project is open-source under the MIT License.

## ✨ Future Enhancements
- **Real-time Data Collection:** Integrate wearable devices for continuous monitoring.
- **Advanced Deep Learning Models:** Explore CNNs and LSTMs for improved feature learning.
- **Multi-modal Analysis:** Combine PPG with eye-tracking and posture analysis for comprehensive cognitive load detection.

---
**Contributors:** [Maithili Badhan]
📫 **Contact:** [maithilibprojects@gmail.com]
