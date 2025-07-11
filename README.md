#  Car Price Prediction ML Project

This project predicts the selling price of used cars using features like brand, year, fuel type, transmission, and kilometers driven. It uses Linear Regression for training and deploys a basic frontend for prediction through a local HTML form.

---

##  Project Goal

To build a Machine Learning model that helps estimate used car prices accurately based on historical data. It includes:

- Data preprocessing
- Model training (Linear Regression)
- Model saving as `.pkl`
- Local web interface using HTML


---

##  Technologies Used

- Python
- Pandas, NumPy
- scikit-learn
- Jupyter Notebook
- HTML (for frontend)
- Pickle (for model saving)

---

##  Workflow

1. **Data Cleaning** – Removed outliers, duplicates, and null values.
2. **Feature Engineering** – Encoded categorical variables.
3. **Model Training** – Used Linear Regression to predict prices.
4. **Model Deployment (Local)** – HTML form for manual input and prediction using saved `.pkl` model.

---

##  Installation

```bash
# Create virtual environment (optional)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

Model Accuracy
Achieved good performance with Linear Regression based on RMSE and R² score metrics (see 948.ipynb).

 Deployment Status
Currently deployed locally via HTML + Python backend

Web interface allows users to manually input car details for price prediction

 Future Enhancements
Integrate with Flask or Streamlit for full web deployment

Add more ML models for better comparison

Add visualization dashboard (e.g., with Seaborn or Plotly)

Author:
Mohit Gautam





