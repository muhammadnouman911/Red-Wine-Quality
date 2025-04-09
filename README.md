
---

# 🍷 **Red Wine Quality Prediction** 🍇

This project uses machine learning models to predict the quality of red wine based on various chemical properties. By exploring different regression techniques, the goal is to find the best model for predicting wine quality, which can be beneficial for wine producers, retailers, and enthusiasts.

---

## 📂 **Project Structure**

- **📂 Decision Tree Regression**: Implementation of the Decision Tree regression model.
- **📂 Linear**: Files for the Linear Regression model.
- **📂 Polynomial**: Files for the Polynomial Regression model.
- **📂 Random Forest Regression**: Implementation of the Random Forest regression model.
- **📂 SVR**: Files for the Support Vector Regression model.
- **📄 red_wine_quality.csv**: The dataset containing chemical properties and wine quality ratings.
- **📄 README.md**: This file, containing project details.

---

## 📊 **Dataset Information**

The dataset, **red_wine_quality.csv**, includes various chemical properties of red wine, such as:

- Fixed acidity
- Volatile acidity
- Citric acid
- Residual sugar
- Chlorides
- Free sulfur dioxide
- Total sulfur dioxide
- Density
- pH
- Sulphates
- Alcohol content

These features are used to predict the quality of wine, which is scored on a scale from 0 to 10.

---

## 🤖 **Machine Learning Models Used**

This project explores several regression models to predict wine quality:

1. **Linear Regression**: A straightforward regression approach that assumes a linear relationship between features and quality.
2. **Decision Tree Regression**: A non-linear model that splits the data based on feature values to predict the output.
3. **Polynomial Regression**: Extends Linear Regression by fitting a polynomial relationship to the data.
4. **Random Forest Regression**: An ensemble model using multiple decision trees to improve prediction accuracy.
5. **Support Vector Regression (SVR)**: Uses support vector machines for regression tasks, particularly useful for non-linear data.

---

## 🚀 **Getting Started**

### 1. Clone the Repository
   ```bash
   git clone https://github.com/yourusername/Red-Wine-Quality.git
   ```

### 2. Install Required Libraries
   Make sure you have Python installed and install the necessary dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### 3. Running the Models
   Open the respective model file (e.g., `Linear/linear_regression.py`) to train and test the model using the provided dataset.

---

## 🔧 **Technologies Used**

- **Python**
- **Scikit-Learn**: For regression models.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib / Seaborn**: For data visualization.

---

## 💡 **Contributing**

Feel free to contribute! Fork the repository, create a branch, and submit a pull request with improvements or bug fixes. If you have any suggestions or features you want to see, create an issue, and we’ll review it.

---

## 📄 **License**

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
