# **Wine Quality Prediction: Analyzing Physicochemical Properties of Vinho Verde**

## **Project Overview**

This project explores the **Wine Quality Dataset**, specifically analyzing **red variants of the Portuguese "Vinho Verde" wine**. The goal is to classify wines as **"good" or "bad"** based on their physicochemical properties and sensory evaluations.

The dataset includes **11 input variables** from physicochemical tests and **1 output variable**, which represents the wine quality on a **0 to 10 scale**. This project leverages machine learning classification models by setting a threshold (e.g., quality ≥7 as **"good"** and the rest as **"bad"**) to predict wine quality.

## **Dataset**

The dataset is sourced from the **UCI Machine Learning Repository**:  
🔗 [Wine Quality Dataset](https://archive.ics.uci.edu/ml/datasets/wine+quality)

**Features:**

- **Input Variables (Physicochemical properties)**

  1. Fixed Acidity
  2. Volatile Acidity
  3. Citric Acid
  4. Residual Sugar
  5. Chlorides
  6. Free Sulfur Dioxide
  7. Total Sulfur Dioxide
  8. Density
  9. pH
  10. Sulphates
  11. Alcohol

- **Output Variable (Sensory evaluation)** 12. **Quality Score** (0 to 10)

## **Analysis and Findings**

- **Exploratory Data Analysis (EDA)**:
  - Examined the distribution of wine quality scores.
  - Visualized the correlation between different physicochemical properties and quality.
- **Feature Engineering & Preprocessing**:
  - Binned quality scores into two categories:
    - **Good wine** (quality ≥7) → `1`
    - **Bad wine** (quality <7) → `0`
  - Checked for missing values and outliers.
- **Machine Learning Model**:
  - Implemented a **Decision Tree Classifier** to predict wine quality.
  - Evaluated performance using **ROC curve** and **AUC score**.
  - Achieved **AUC of 0.88**, indicating strong predictive performance.

## **Technologies Used**

- Python
- Pandas
- NumPy
- Matplotlib / Seaborn (for visualization)
- Scikit-Learn (for machine learning)
- Jupyter Notebook

## **How to Run**

1. Clone this repository:
   ```sh
   git clone https://github.com/yourusername/Wine-Quality-Prediction.git
   ```
2. Install required dependencies:
   ```sh
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Open the Jupyter Notebook:
   ```sh
   jupyter notebook wine_quality_analysis.ipynb
   ```

## **Results**

The project successfully **identifies key factors** affecting wine quality and provides a **machine learning model** to classify wines. **The detailed analysis and visualizations are available in the notebook.**
