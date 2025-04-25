# Principal Component Analysis (PCA) on Iris Dataset

This project demonstrates the use of **Principal Component Analysis (PCA)** for dimensionality reduction and visualization on the popular **Iris dataset**. The analysis includes preprocessing, applying PCA, and visualizing the reduced dimensions.

## 📁 Files

- `Principal_Component_Analysis (1).ipynb` – The Jupyter Notebook containing the full code for PCA analysis and visualization.
- `README.md` – Project documentation (this file).

## 📊 Dataset

The **Iris dataset** contains 150 samples with 4 features:
- Sepal length
- Sepal width
- Petal length
- Petal width

There are 3 species:
- Iris-setosa
- Iris-versicolor
- Iris-virginica

## 🧠 Techniques Used

- **Standardization** using `StandardScaler`
- **Dimensionality Reduction** using `PCA` from `sklearn.decomposition`
- **Data Visualization** using `seaborn` and `matplotlib`

## 📌 How to Run

1. Clone the repository or download the notebook.
2. Install dependencies (preferably using a virtual environment):
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn
   ```
3. Open the notebook:
   ```bash
   jupyter notebook "Principal_Component_Analysis (1).ipynb"
   ```

## 📷 Output Example

The notebook includes a 2D scatter plot showing PCA-reduced data points colored by species.

## ✅ Output Interpretation

PCA helps to visualize how separable the classes (species) are in lower dimensions. The first two principal components usually capture the most variance in the dataset, giving us insight into the structure of the data.


