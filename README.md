
# Manufacturing Defects Predict

This project focuses on predicting manufacturing defects using machine learning techniques.
A classification model is trained on real-world manufacturing process data to identify whether a product or process will result in a defect.

The final model achieves an **accuracy of 96%**, demonstrating strong predictive performance.

---

## 📁 Repository Structure

| File | Description |
|------|-------------|
| `manufacturing_defect_dataset.csv` | Raw manufacturing dataset containing process and quality features |
| `fault.ipynb` | Jupyter Notebook for data preprocessing, feature engineering, model training, and evaluation |
| `Manufacturing_defect_model.pkl` | Trained machine learning model for defect prediction |

---

## 🎯 Objective

To build a reliable **defect prediction system** that helps manufacturers:
- Detect potential defects early
- Improve quality control
- Reduce downtime and operational losses

---

## 📊 Dataset Description

The dataset includes manufacturing and operational features such as:
- Production metrics
- Quality indicators
- Maintenance and downtime information
- Energy and workforce-related attributes

The target variable is **`DefectStatus`**, indicating whether a defect occurred.

---

## 🧠 Model Used

- **Random Forest Classifier**
  - Handles non-linear relationships effectively
  - Robust to noise and outliers
  - Provides feature importance for interpretability

---

## 📈 Model Performance

- **Accuracy:** **96%**
- Additional evaluation metrics and visualizations are available in `fault.ipynb`.

---

## ▶️ How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/Naman0911/Manufacturing-Defects-Predict.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Manufacturing-Defects-Predict
   ```

3. Install dependencies:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```

4. Run the notebook:
   ```bash
   jupyter notebook fault.ipynb
   ```

---

## 📌 Notes

- Feature engineering plays a key role in achieving high accuracy.
- The trained model can be reused or retrained with new manufacturing data.
- This project is suitable for educational and industrial ML practice.

---

## 📜 License

This project is open-source and intended for learning and demonstration purposes.
