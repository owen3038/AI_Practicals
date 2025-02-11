# AI_Practicals

# 🏡 Housing Price Prediction using Machine Learning

## 📌 Project Overview
This project applies **Regression Machine Learning techniques** to analyze and predict housing prices.  
The dataset includes features such as **property size, number of bedrooms, location, rental price, and socioeconomic factors**.  
We use **Linear Regression and Random Forest Regressor** to train and evaluate the model.  

---

## 📂 Dataset
- **Dataset Name:** Housing.csv
- **Source:** Public Housing Dataset (from Kaggle, UCI ML Repository, or other open sources)
- **Features:**
  - `price` - Target variable (House price)
  - `area` - Size of the property (square feet)
  - `bedrooms` - Number of bedrooms
  - `bathrooms` - Number of bathrooms
  - `stories` - Number of floors in the house
  - `mainroad` - Whether the house is on the main road (Yes/No)
  - `guestroom` - Whether the house has a guest room (Yes/No)
  - `basement` - Presence of a basement (Yes/No)
  - `hotwaterheating` - Hot water heating system available (Yes/No)
  - `airconditioning` - Whether the house has air conditioning (Yes/No)
  - `parking` - Number of parking spaces available
  - `prefarea` - Preferred area (Yes/No)
  - `furnishingstatus` - Status of furnishing (Fully Furnished, Semi-Furnished, Unfurnished)

---

## 📊 Machine Learning Models Used
1. **Linear Regression**
2. **Random Forest Regressor**

---

## 🚀 Data Preprocessing & Feature Engineering
- **Converted categorical variables** using Label Encoding & One-Hot Encoding.
- **Normalized numerical features** using StandardScaler.
- **Split data** into 80% training and 20% testing sets.

---

## 📈 Model Evaluation Metrics
| Model                 | MAE (Mean Absolute Error) | MSE (Mean Squared Error) | R² Score |
|-----------------------|-------------------------|-------------------------|----------|
| **Linear Regression** | _X.XX_                   | _X.XX_                   | _X.XX_   |
| **Random Forest**     | _X.XX_                   | _X.XX_                   | _X.XX_   |

✅ **Random Forest typically performs better due to its ability to capture non-linear relationships.**

---

## 📌 How to Run This Project
# 1️⃣ Clone the GitHub repository
git clone https://github.com/owen3038/housing-price-prediction.git

# 2️⃣ Navigate into the project folder
cd housing-price-prediction

# 3️⃣ (Optional) Create a virtual environment (recommended)
python -m venv venv
source venv/bin/activate  # Mac/Linux
venv\Scripts\activate  # Windows

# 4️⃣ Install dependencies
pip install -r requirements.txt

# 5️⃣ Launch Jupyter Notebook
jupyter notebook

# 6️⃣ Open the notebook (housing_price_prediction.ipynb) and run all cells


📌 How to Save & Push to GitHub
If you made any changes and want to push them to GitHub:
git add .
git commit -m "Updated Housing Price Prediction Model"
git push origin main



 **✨ Author: MICHAEL ONWUACHI**
**📧 onwuachiichael@gmail.com
🔗[ GitHub Profile](https://github.com/owen3038)
**

