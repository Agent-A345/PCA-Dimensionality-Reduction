## 📉 PCA Dimensionality Reduction

A machine learning project built using Python and Jupyter Notebook that applies Principal Component Analysis (PCA) to reduce the dimensionality of high-dimensional datasets while preserving maximum information. The project demonstrates data preprocessing, feature scaling, variance analysis, dimensionality reduction, visualization, clustering, and classification using the Human Activity Recognition (HAR) dataset.

## 🚀 Features
* **Principal Component Analysis (PCA)** – Reduce high-dimensional data into informative components.
* **Dimensionality Reduction Pipeline** – Transform large feature spaces into compact representations.
* **Explained Variance Analysis** – Determine the optimal number of principal components.
* **Feature Scaling & Standardization** – Normalize features before PCA transformation.
* **2D & 3D Data Visualization** – Visualize reduced feature spaces for better interpretation.
* **Classification Performance Comparison** – Evaluate models before and after PCA.
* **Clustering Analysis** – Explore cluster formation in reduced-dimensional space.
* **Exploratory Data Analysis (EDA)** – Analyze feature distributions and correlations.
* **Model Performance Optimization** – Improve computational efficiency using reduced features.
* **Real-World HAR Dataset** – Practice dimensionality reduction on sensor-based activity recognition data.

## 📂 Project Structure
PCA-Dimensionality-Reduction/  
├── pca_workflow.ipynb  
├── test.csv    
├── train.csv    

## 💡 Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
  
## 🛠️ How to Run
1. **Clone the repository**:
```
git clone https://github.com/Agent-A345/PCA-Dimensionality-Reduction.git
```
2. **Navigate to the project folder**:
```
cd PCA-Dimensionality-Reduction
```
3. **Install required libraries**
```
pip install pandas numpy matplotlib seaborn jupyter scikit-learn 
```
4. **Run the notebook**
```
jupyter notebook
```
5. **Open**
```
pca_workflow.ipynb
```
## 🎮 Analysis Performed
**Data Preprocessing**
* Cleaned, merged, and standardized the training and testing datasets.

**Exploratory Analysis**
* Visualized feature distributions, correlations, and class distributions.

**Feature Scaling**
* Standardized numerical features prior to PCA transformation.

**Principal Component Analysis**
* Applied PCA and analyzed cumulative explained variance to select optimal components.

**Dimensionality Reduction**
* Generated lower-dimensional feature representations while preserving key information.

**Visualization**
* Created 2D and 3D visualizations of principal components.

**Model Evaluation**
* Compared clustering and classification performance using PCA-transformed features.

## 🎯 Project Objective
This project helps users:
* Understand Principal Component Analysis
* Learn dimensionality reduction techniques
* Reduce computational complexity for machine learning models
* Visualize high-dimensional datasets effectively
* Build strong foundations in feature engineering and unsupervised learning

## 🔄 Future Enhancements
* Kernel PCA implementation
* t-SNE and UMAP comparison
* Interactive PCA visualization dashboard
* Automated component selection

## 📦 Dataset Used
This project uses the [Human Activity Recognition with Smartphones Dataset](https://www.kaggle.com/datasets/uciml/human-activity-recognition-with-smartphones) obtained from Kaggle.

## 📜 License
This project is licensed under the MIT License.
