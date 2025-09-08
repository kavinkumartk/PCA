# 📚 PCA Visualization of Wine Quality Dataset

## ✅ Objective
Perform dimensionality reduction using PCA to visualize the wine quality dataset in 2D space and observe how samples distribute based on wine quality.

---

## ✅ Dataset
- **File**: `winequality-white.csv`
- **Description**: White wine dataset with physicochemical features and wine quality as target.
- **Separator**: `;`

---

## ✅ Steps Performed

1. **Load Dataset**
2. **Separate Features and Target**
3. **Scale Features**
4. **Apply PCA (2 Components)**
5. **Visualize PCA Results**
6. 
---

## ✅ Example Output

(<img width="1052" height="873" alt="image" src="https://github.com/user-attachments/assets/fab09b2d-b892-4952-9710-7915916dfcbe" />)  
*Figure: PCA scatter plot showing samples colored by wine quality.*

---

## ✅ Usage Instructions
1. Place `winequality-white.csv` and `pca_visualization.png` in the working directory.
2. Install required packages:
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn
    ```
3. Run the script to generate the PCA scatter plot.

---

## ✅ Insights
- Visualizes the relationship between wine quality and input features in a reduced 2D space.
- Useful for detecting clusters, outliers, and variance explained by principal components.
