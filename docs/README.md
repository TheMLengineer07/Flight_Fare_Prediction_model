# ✈️ Flight Fare Prediction Model

* This project is a machine learning-based solution to predict flight fares using various input features like airline, source, destination, departure 
  time, duration, number of stops, and more. 
  The model was trained using historical flight data and deployed for real-time fare prediction.
  
## 🚀 Live Demo
Check out the deployed model here:  

👉 [Flight Fare Prediction App](https://flight-fare-prediction-model-rcoz.onrender.com)



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

2. **Create and active virtual enviroment**

   ```bash
   python -m venv myenv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**

   ```pip install -r requirements.txt```

4. **Run the app**

   ``` streamlit run app.py```

⚙️ Features & Input Parameters

   *  Airline (e.g., Indigo, Jet Airways)

   *  Source and Destination cities

   *  Date and time of departure and arrival

   *  Duration of flight

   *  Total number of stops

 📈 Model Performance
 
   * Model: Random Forest Regressor

   * Evaluation Metrics:

   * R² Score: ~0.95

   * MAE and RMSE within acceptable bounds

 📦 Tech Stack
 
   * Programming Language: Python

   * Libraries: Scikit-learn, Pandas, NumPy, Streamlit, Pickle

   * Deployment: Render

 ## 🚀 Deployment on Render
 
   * This project is deployed on **Render**, allowing real-time flight fare predictions.

 ### 🌐 Steps to Deploy:
 
  1. Push your latest code to GitHub.
   
  2. Log in to **Render** and create a **new Web Service**.
   
  3. Link your GitHub repository and configure build & start commands.
   
  4. Deploy and monitor logs.

🔗 **Live Deployment**: [Flight Fare Prediction](https://flight-price-prediction-api.herokuapp.com/)


📌 Future Enhancements

   * Add real-time data input via API

   * Improve UI/UX on the frontend

   * Integrate CI/CD for auto-deployment

🙋‍♂️ Author


    Prabhav @TheMLengineer07
    GitHub Profile

📝 License

  This project is licensed under the MIT License - see the LICENSE file for details.


  ---

    Let me know if you:
    - Want a version with badges (e.g. Streamlit live demo, GitHub stars)
    - Want help creating a logo/banner for the top of the README
    - Need to write a blog or portfolio summary based on this

    Happy shipping! 💼✨








