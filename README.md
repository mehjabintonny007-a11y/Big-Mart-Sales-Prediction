# Big Mart Sales Prediction 🛒

## 📌 Introduction
This project predicts the sales of products across different Big Mart outlets using machine learning techniques.  
The goal is to build a regression model that can accurately forecast sales based on product and outlet features.

---

## 📊 Dataset
The dataset contains information about products and outlets, including:
- **Item_Identifier**: Unique product ID  
- **Item_Weight**: Weight of the product  
- **Item_Fat_Content**: Fat level of the product (Low Fat / Regular)  
- **Item_Visibility**: Visibility of the product in the store  
- **Item_Type**: Category of the product (Dairy, Meat, Soft Drinks, etc.)  
- **Item_MRP**: Maximum Retail Price  
- **Outlet_Identifier**: Unique store ID  
- **Outlet_Establishment_Year**: Year when the outlet was established  
- **Outlet_Size**: Size of the outlet (Small / Medium / Large)  
- **Outlet_Location_Type**: Location tier of the outlet  
- **Outlet_Type**: Type of outlet (Supermarket, Grocery Store, etc.)  
- **Item_Outlet_Sales**: Target variable (sales amount)

---

## ⚙️ Requirements
Install the following Python libraries before running the project:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
🚀 How to Run
Clone the repository:

bash
git clone https://github.com/your-username/BigMart-Sales-Prediction.git
Navigate to the project folder:

bash
cd BigMart-Sales-Prediction
Run the Jupyter Notebook or Python script:

bash
jupyter notebook BigMart.ipynb
or

bash
python bigmart.py
📈 Model
The project uses XGBoost Regressor with tuned parameters:

n_estimators=200

max_depth=6

learning_rate=0.1

subsample=0.8

colsample_bytree=0.8

reg_alpha=0.1

reg_lambda=1

📊 Visualizations
Distribution plots for numeric features (Item_Weight, Item_MRP, Item_Outlet_Sales)

Count plots for categorical features (Item_Fat_Content, Item_Type, Outlet_Type)

Boxplots and scatterplots to explore relationships between features and sales

🙌 Contributors
Mehjabin

📌 Future Work
Hyperparameter tuning with GridSearchCV

Feature engineering for better model accuracy

Deployment of the model using Flask or Streamlit
