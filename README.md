# ✈️ Flight Fare Prediction Model

* This project is a machine learning-based solution to predict flight fares using various input features like airline, source, destination, departure time, duration, number of stops, and more. 
  The model was trained using historical flight data and deployed for real-time fare prediction.
  

# 📌 Project Overview

- **Objective**: Predict the flight price based on several travel-related parameters.
- **Model Used**: Random Forest Regressor
- **Framework**: Python, Scikit-learn, Pandas, NumPy
- **Deployment**: Deployed on Render (or insert actual deployment link if available)
- **Frontend**: Streamlit (optional, if applicable)

---

# 📂 Project Structure

Flight_Fare_Prediction_model/

│

├── app.py              # Streamlit app for UI

├── flight_rf.pkl       # Trained ML model (Git LFS tracked)

├── requirements.txt    # Dependency list

├── README.md           # Documentation

└── data/               # (Optional) Dataset files




## 🚀 How to Run the Project Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/TheMLengineer07/Flight_Fare_Prediction_model.git
   cd Flight_Fare_Prediction_model

2  Create and active virtual enviroment

   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate

3  Install dependencies

   pip install -r requirements.txt

4  Run the app

   streamlit run app.py

⚙️ Features & Input Parameters

 *  Airline (e.g., Indigo, Jet Airways)

 *  Source and Destination cities

 *  Date and time of departure and arrival

 *  Duration of flight

Total number of stops




