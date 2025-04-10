 # Forest Cover Type Prediction using Machine Learning

This project predicts the type of forest cover based on cartographic and soil attributes of a 30m x 30m patch of forest land using the XGBoost machine learning algorithm.

---

# Problem Statement

Given cartographic variables such as elevation, slope, soil type, and wilderness area, predict the forest cover type (1 to 7) of a given land patch.

---

#  Dataset

- 📄 File: `forest prediction.csv`
- Contains:
  - 54 features (e.g., Elevation, Aspect, Slope, Soil Types)
  - `Cover_Type`: The target variable (Classes 1 to 7)

---

#  Tools & Technologies

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost

---

#  Approach

1. **Data Preprocessing**
   - Removed non-essential columns (`Id`)
   - Standardized features using `StandardScaler`
   - Adjusted class labels from 1–7 to 0–6

2. **EDA (Exploratory Data Analysis)**
   - Visualized class distribution
   - Explored correlations among features

3. **Model Training**
   - Used `XGBoostClassifier` with `mlogloss` as the evaluation metric
   - Achieved **~86–87% accuracy**

4. **Evaluation**
   - Classification report
   - Confusion matrix
   - Feature importance plot

---

#  Results

- ✅ Accuracy: ~86.5%
- 📊 Confusion matrix and classification metrics showed reliable multi-class classification performance.

---

#  Visualizations

- Forest Cover Type Distribution
- Correlation Heatmap
- Confusion Matrix
- Feature Importances from XGBoost

---

# How to Run

Run the script or Jupyter Notebook:

python python forest_cover_prediction_with_visuals.py

or open the notebook:

Forest Cover Notebook.ipynb

# Requirements

scikit-learn

xgboost

pandas

matplotlib

seaborn

You can install all dependencies using:

bash pip install -r requirements.txt

# Contributing

Contributions are welcome! If you find bugs or have suggestions, feel free to raise an issue or open a pull request.

# Contact

Created by Revati Mahajan
🔗 LinkedIn • 🔗 GitHub

# License

This project is open-source and available under the MIT License.
