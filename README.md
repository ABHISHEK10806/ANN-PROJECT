📊 Project Title: Profit Prediction using ANN

Introduction:
Is project mein humne Artificial Neural Network (ANN) ka use karke Profit predict kiya hai. Dataset SampleSuperstore ka hai, jisme Sales, Quantity aur Discount jaise features available hain.

Dataset & Preprocessing:
Sabse pehle dataset load kiya aur sirf required columns select kiye:
👉 Sales, Quantity, Discount aur Profit
Missing values nahi the, isliye data clean tha.
Uske baad Train-Test Split (80–20) kiya aur StandardScaler se data normalize kiya.

Model Architecture:
ANN model Keras Sequential API se banaya gaya:

Input layer: 3 features

First Hidden Layer: 16 neurons (ReLU)

Second Hidden Layer: 8 neurons (ReLU)

Output Layer: 1 neuron (Regression)

Training Details:

Optimizer: Adam

Loss Function: Mean Squared Error

Metric: MAE

Epochs: 50

Model Performance:
Training ke baad model ka Test MAE approx 53 aaya.
Iska matlab hai ki average prediction error around 53 units hai.

Prediction:
Model ne Profit ke liye kaafi cases mein positive aur negative values dono predict ki, jo real-world business scenario ko represent karta hai.

Conclusion:
Ye project dikhata hai ki ANN business data se profit prediction ke liye use kiya ja sakta hai.
Future mein aur features add karke aur hyperparameter tuning se model ki accuracy improve ki ja sakti hai.
