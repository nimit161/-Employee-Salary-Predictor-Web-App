Employee Salary Predictor
A smart, responsive, and ML-powered web application that predicts an employee’s monthly salary based on their age, gender, education, experience, occupation, working hours, and country. This project combines a trained machine learning model with a modern frontend UI using Flask, Chart.js, Lottie animations, and PDF export functionality.

🚀 Live App:
🔗 https://employee-salary-predictor-web-app-js5t.onrender.com/

🧠 Features
✅ Machine Learning–powered salary predictions
✅ Responsive UI with Light/Dark Mode toggle
✅ Real-time salary comparison chart (You vs Average)
✅ Personalized greeting based on user name
✅ PDF download of the chart for reporting
✅ Lottie animations for modern UX
✅ Mobile-friendly and fully deployable


Run the app
python app.py Then open http://127.0.0.1:5000 in your browser.

🔁 Model Training Explanation You can retrain the model by running: python train_model.py Loads & cleans the dataset

Maps income >50K → ₹60K and <=50K → ₹30K

Converts it into monthly salary

Label-encodes categorical features

Scales numerical data

Trains a Linear Regression model

Saves .pkl files for use in prediction

🧠 How Prediction Works User enters details in a clean web form

Flask backend receives form via POST

Input is encoded using saved LabelEncoders

Scaled using StandardScaler

Regression model (income_model.pkl) predicts real salary (₹)

Result is shown with:

Name

Salary value

Chart.js bar chart

PDF Download button button
