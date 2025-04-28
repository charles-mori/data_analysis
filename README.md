# Dataset Analysis

## 📅 Overview
This project demonstrates how to load, explore, analyze, and visualize the Iris dataset using Python. It utilizes libraries like `pandas`, `matplotlib`, `seaborn`, and `sklearn`.

The project is divided into three main tasks:
- **Task 1:** Loading and exploring the dataset.
- **Task 2:** Performing basic data analysis.
- **Task 3:** Creating visualizations.

---

## 📊 Requirements
Make sure you have the following Python libraries installed:

```bash
pip install pandas matplotlib seaborn scikit-learn
```

---

## 🗂️ Project Structure
- `data_analysis.ipynb` : Jupyter notebook containing data loading, exploration, analysis, and visualization.

---

## 📈 Tasks Breakdown

### Task 1: Load and Explore the Dataset
- Load the Iris dataset from `sklearn.datasets`.
- Display the first few rows.
- Check data types and missing values.
- Clean the dataset by dropping missing values (none found).

### Task 2: Basic Data Analysis
- Compute basic statistics with `.describe()`.
- Group the dataset by species and calculate mean values.

**Observations:**
- Setosa generally has smaller sepal and petal sizes.
- Virginica tends to have the largest petal measurements.

### Task 3: Data Visualization
- **Line Chart:** Petal length trend across samples.
- **Bar Chart:** Average petal length by species.
- **Histogram:** Distribution of sepal width.
- **Scatter Plot:** Sepal length vs. petal length, differentiated by species.

Each plot is customized with:
- Titles
- Axis labels
- Legends
- Different colors and styles

---

## 📊 Final Observations
- No missing values were found.
- Virginica flowers have the largest petals.
- Sepal width most commonly centers around 3 cm.
- Scatter plots show clear visual separation of species.

---

## 🔄 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/charles-mori/data_analysis
   ```
2. Navigate to the project folder:
   ```bash
   cd data-analysis
   ```
3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Open and run `data_analysis.ipynb`.

---

## 📆 License
This project is licensed under the [MIT License](LICENSE).

---

> Made with ❤️ by Charles Mori

