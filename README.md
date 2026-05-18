Predictive Maintenance Dashboard for Aircraft Engine RUL Analysis

Overview:

This project is an AI-driven predictive maintenance system developed for aircraft engine Remaining Useful Life (RUL) prediction using the NASA C-MAPSS turbofan engine dataset. The project combines deep learning and dashboard-based visualization to simulate real-time engine health monitoring and predictive analytics.
The system uses a hybrid CNN-BiLSTM model to analyze multivariate time-series sensor data and predict engine degradation trends before failure occurs.

Features:
Aircraft engine RUL prediction using deep learning
Hybrid 1D CNN + BiLSTM architecture
Time-series sensor data analysis
Data preprocessing and sequence generation
Interactive dashboard for monitoring predictions
Engine degradation trend visualization
RMSE/MSE-based model evaluation
Simulated predictive maintenance workflow

Tech Stack:
Python
TensorFlow / Keras
CNN
Bidirectional LSTM (BiLSTM)
Pandas
NumPy
Scikit-learn
Matplotlib

Dataset:
NASA C-MAPSS Turbofan Engine Dataset
Dataset used: FD001 subset
Project Workflow
Data Loading and Preprocessing
Sensor Feature Selection
Sequence Generation using Sliding Window
CNN-BiLSTM Model Training
Remaining Useful Life (RUL) Prediction
Model Evaluation using RMSE and MSE
Dashboard Visualization and Monitoring
Model Architecture
1D CNN for spatial feature extraction
Bidirectional LSTM for temporal dependency learning
Dense layers for RUL regression output

Results:
The model successfully predicts engine degradation patterns and estimates Remaining Useful Life (RUL) from sensor readings, supporting predictive maintenance and condition monitoring applications.

Future Improvements:
Real-time IoT sensor integration
Deployment on cloud platforms
Attention-based deep learning models
Live streaming data support
Edge AI deployment for industrial systems

Author:
Final Year CSE-AIML Student | AI/ML & Deep Learning Enthusiast
