# ☀️ Predicting Solar Energy Production Using Machine Learning
A simple machine learning project that predicts how much solar energy a power plant will produce based on weather conditions.

### 📌 What is this Project?
This project uses Machine Learning to guess (predict) how much electricity a solar power plant will make. It looks at weather data like sunshine, wind speed, temperature, etc., and tells us the expected energy output.
👥 Team Members
Table
Name	Role
Laiba Kanwal	Team Member
Alisha Tabasum	Team Member
This project was built together as a team effort.
🧠 Models We Used
We trained and tested 6 different Machine Learning models:
Linear Regression – Draws a straight line to predict values
Decision Tree – Asks yes/no questions to reach a decision
Random Forest – Uses many decision trees together for better accuracy
Gradient Boosting – Fixes mistakes step by step to improve results
Support Vector Machine (SVR) – Finds the best boundary line for prediction
Neural Network (MLP) – A simple brain-like network that learns patterns
📊 Dataset
File: Solar Power Plant Data.csv
Features (Input):
🌬️ WindSpeed
☀️ Sunshine
🌡️ AirPressure
🔆 Radiation
🌤️ AirTemperature
💧 RelativeAirHumidity
Target (Output):
⚡ SystemProduction
⚙️ How It Works
Load Data – Read the CSV file
Clean & Prepare – Check data info
Split Data – 80% training, 20% testing
Scale Features – StandardScaler se normalize kiya
Train Models – Har model ko train kiya
Test Models – Unseen data pe check kiya
Compare Results – Best model dhunda
Hyperparameter Tuning – Random Forest ko aur behtar banaya
Visualize – Charts banaye samajhne ke liye
📈 Evaluation Metrics
MAE – Average error
MSE – Bigger mistakes ko zyada punish karta hai
R² Score – 1.0 ke qareeb = best model
Cross-Validation – Har jagah test karke confirm kiya
🚀 How to Run
bash
Copy
pip install pandas matplotlib scikit-learn
Then run the Python script / Jupyter Notebook!
📊 Visualizations Included
🥧 Pie Chart – Accuracy comparison
📊 Bar Chart – Top 5 important features
🔵 Scatter Plot – Actual vs Predicted
🥧 Pie Chart – Cross-validation scores
🏆 Best Performing Model
Random Forest usually sabse behtar results deta hai. Isliye isi pe Hyperparameter Tuning bhi ki gayi hai!
🛠️ Tech Stack
Table
Tool	Purpose
Python	Programming language
Pandas	Data handling
Matplotlib	Charts & graphs
Scikit-Learn	ML models
🙏 Acknowledgements
Special thanks to our teachers and mentors who guided us throughout this project.
Project by: Laiba Kanwal & Alisha Tabasum
⭐ If you like this project, give it a star on GitHub!
