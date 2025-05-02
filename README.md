# K-Nearest Neighbors (KNN) Classification - Iris Dataset 

## Objective

- Apply KNN classification to a real-world dataset.
- Normalize features to ensure fair distance computation.
- Experiment with different values of K and choose the best one.
- Evaluate the model using accuracy, confusion matrix, and classification report.
- Visualize how accuracy varies with K.

---

## Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## Dataset

- **Name**: Iris Dataset
- **Source**: Built-in `sklearn.datasets`
- **Features**: Sepal length, Sepal width, Petal length, Petal width
- **Classes**: Setosa, Versicolor, Virginica

---

## Steps Followed

1. **Data Loading**: Loaded the Iris dataset from `sklearn.datasets`.
2. **Preprocessing**: Normalized the features using `StandardScaler`.
3. **Train-Test Split**: 80% training and 20% testing.
4. **Model Training**: Trained KNN models with K values from 1 to 20.
5. **Evaluation**: Measured accuracy, plotted performance graph, confusion matrix, and classification report.
6. **Result**: Best performance observed at **K = 6**, achieving **100% accuracy** on the test set.

---

## Visualization

- A line graph showing accuracy for different values of K.
- Helpful for selecting the optimal K.

---

## Results

- **Confusion Matrix**: Perfect classification across all 3 species.
- **Accuracy**: 100%
- **Precision, Recall, F1-Score**: All metrics = 1.00

---

## How to Run

1. Clone this repository.
2. Open the notebook or script file (`.ipynb` or `.py`) in Jupyter/Colab.
3. Run all cells sequentially.
