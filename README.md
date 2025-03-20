# 🚖 Uber Rides Prediction

![Uber Rides Prediction](https://img.shields.io/badge/Flask-App-blue) 
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Linear%20Regression-green)  
A Machine Learning-powered web application that predicts the number of weekly Uber rides based on given input parameters.

## 🌟 Project Overview
This project utilizes **Linear Regression** to predict the number of weekly Uber rides based on various factors.  
The model is trained on a dataset containing ride-related data and is deployed as a **Flask web application** on Render.

## 🔗 Live Demo
🔹 **Try the application here:** [Uber Rides Prediction](https://uber-ride-prediction.onrender.com/predict)  

## 🛠️ Tech Stack
- **Python** (pandas, numpy, scikit-learn, pickle)
- **Machine Learning** (Linear Regression)
- **Flask** (Backend API)
- **HTML/CSS** (Frontend)
- **Deployment** (Render)

## 📂 Project Structure
Uber-Rides-Prediction/
│── templates/
│   ├── index.html          # Frontend UI
│── static/
│   ├── styles.css          # Stylesheet (if applicable)
│── taxi.csv                # Dataset
│── uber_model.pkl          # Trained ML Model
│── model.py                # Model Training Script
│── app.py                  # Flask Web Application
│── requirements.txt        # Dependencies
│── README.md               # Project Documentation

## ⚡ How to Run Locally
1. **Clone the repository:**
   ```bash
   git clone https://github.com/RNNivash/Uber-Rides-Prediction.git
   cd Uber-Rides-Prediction
   
## ⚡ Install dependencies:
pip install -r requirements.txt

## ⚡ Run the Flask app:
python app.py

## 🔮 Model Training
	•	The dataset (taxi.csv) is loaded using pandas.
	•	Features (X) and target variable (y) are extracted.
	•	A Linear Regression model is trained using scikit-learn.
	•	The trained model is saved as uber_model.pkl using pickle.
	•	Flask API loads the model to predict weekly rides.

## 🤝 Contributing

Feel free to open issues or contribute to improve this project.
	1.	Fork the repo
	2.	Create a new branch (git checkout -b feature-branch)
	3.	Commit changes (git commit -m "Added feature")
	4.	Push to branch (git push origin feature-branch)
	5.	Open a Pull Request

## 📝 License

This project is MIT Licensed.

## You can reach out to me via:

📧 Email: hello.nivashinsights@gmail.com
🔗 LinkedIn: Nivash R N
🌐 Portfolio: rnnivash.github.io/My_Port

Let me know how I can assist you! 🚀
