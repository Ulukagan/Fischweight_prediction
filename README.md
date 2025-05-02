🎣 Fish Weight Prediction App
This repository contains a Streamlit-based web application for predicting the weight of a fish based on its physical characteristics using a trained XGBoost model.

📁 Repository Structure
├── Fish.csv                # Dataset with fish species and measurements
├── README.md               # Project documentation
├── best_model.json         # Trained XGBoost model (saved in JSON format)
├── classes.npy             # Label encoder classes
├── main.py                 # Streamlit app code
├── model.py                # Model training and evaluation code
├── prediction.py           # Prediction utilities
└── requirements.txt        # Python dependencies
🚀 How to Run the App
Clone the repository:
git clone https://github.com/<your-username>/Fishweight_prediction.git
cd Fishweight_prediction
Create a virtual environment and install dependencies:
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
pip install -r requirements.txt
Run the Streamlit app:
streamlit run main.py
Open your browser: Streamlit will automatically open the app at http://localhost:8501

🧠 Model
The model is trained using XGBoost Regressor.
Labels (fish species) are encoded with sklearn's LabelEncoder.
The model and encoder classes are loaded from best_model.json and classes.npy respectively.

🐟 Features
Input fish measurements through an interactive UI
Get instant predictions on fish weight
Lightweight and easy to deploy

📦 Requirements
streamlit==1.3.1
pandas==1.3.5
xgboost==1.5.1
numpy==1.21.5
sklearn==0.0
scikit-learn==1.0.2
seaborn==0.11.2
matplotlib==3.5.1
hyperopt==0.2.7

✍️ Author
Created by Ulukagan
