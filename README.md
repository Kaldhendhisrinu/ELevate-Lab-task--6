# 🌸 K-Nearest Neighbors (KNN) Classification - Iris Dataset

This project demonstrates how to implement the K-Nearest Neighbors (KNN) algorithm for classification using the Iris flower dataset. It includes preprocessing, model training, evaluation, and visualization of decision boundaries using the first two features.

---

## 📌 Objective

- Understand and apply KNN for classification tasks.
- Visualize decision boundaries to see how the model differentiates classes.
- Experiment with different `K` values to observe their effect on performance.

---

## 🛠️ Tools & Libraries

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## 📂 Dataset

- **Name**: Iris Dataset
- **Source**: UCI Machine Learning Repository or `Iris.csv` file
- **Columns**:
  - SepalLengthCm
  - SepalWidthCm
  - PetalLengthCm
  - PetalWidthCm
  - Species (target)

---

## 📈 Steps Performed

1. **Data Loading**
   - Read the dataset using `pandas`.

2. **Preprocessing**
   - Drop unnecessary columns (like `Id`).
   - Normalize features using `StandardScaler`.

3. **Train/Test Split**
   - Split the data into training and testing sets (70:30 ratio).

4. **Model Training**
   - Use `KNeighborsClassifier` from `sklearn`.
   - Try different values of `K` (1 to 10).

5. **Model Evaluation**
   - Calculate accuracy, confusion matrix, and classification report.

6. **Visualization**
   - Plot accuracy vs K.
   - Visualize decision boundaries using the first 2 features.

---

## 📊 Results

- Best accuracy achieved for: **K = _[X]_**
- High classification performance shown by precision, recall, and F1-score.
- Decision boundaries show how the model separates different species.

---

## 📷 Sample Output

![KNN Decision Boundary Plot](./assets/knn_decision_boundary.png)  <!-- optional image -->

---

## 🧠 Learnings

- KNN is intuitive and effective for low-dimensional classification problems.
- Choosing the right value of `K` is crucial for performance.
- Normalization improves distance-based algorithm performance.

---

## 🚀 How to Run

1. Clone the repo or download the `.ipynb` notebook.
2. Ensure you have the required libraries installed:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
