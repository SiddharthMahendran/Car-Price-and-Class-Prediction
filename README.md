Car-Price-and-Class-Prediction 

Car-Price-and-Class-Prediction is a data analysis and machine learning project that aims to efficiently predict the class and price of a car. 

Table of Contents 

   * Dataset 1: Car Classification 
   * Description 
   * Tasks 
   * Results and Metrics 
   * Dataset 2: Car Price Regression 
   * Description 
   * Tasks 
   * Results and Metrics 
   * Dependencies 
   * Contributing 

Dataset 1: Car Classification 

Description 

The first dataset, cars_class.csv, is a multi-class classification dataset containing information about cars. It consists of 719 samples with 18 numerical features. The target variable is the class of the car, which can be one of the following: 0 (bus), 1 (Opel Manta), 2 (Saab), or 3 (Van). The dataset requires preprocessing and analysis to build a predictive model. 

Tasks 

   * Load the data into the code. 
   * Split the data into training and testing sets. 
   * Apply preprocessing techniques to the data. 
   * Implement and compare different machine learning techniques. 
   * Tune the parameters of the selected models. 
   * Build a final model named 'final_model'. 
   * Evaluate the 'final_model' on the test data. 
   * Report accuracy, F1-score, and display the confusion matrix. 
   * Identify and report the importance of different features. 

Results and Metrics 

   * Accuracy: 0.8125 
   * F1-score: 0.8112231469625836 
   * Confusion Matrix: [[44 0 0 0] 
                        [1 10 17 2] 
                        [1 14 16 4] 
                        [1 0 0 34]] 

Dataset 2: Car Price Regression 

Description 

The second dataset, cars_price.csv, is a regression dataset that contains information about car prices. It consists of 206 samples with 25 features. The target variable is the price of the car. The dataset requires preprocessing and analysis to build a regression model that predicts car prices. 

Tasks 

   * Load the data into the code. 
   * Split the data into training and testing sets. 
   * Apply preprocessing techniques to the data. 
   * Implement and compare different machine learning techniques. 
   * Tune the parameters of the selected models. 
   * Build a final model named 'final_model'. 
   * Evaluate the 'final_model' on the test data. 
   * Report MSE, MAE, and R2-score. 
   * Identify and report the importance of different features. 

Results and Metrics 

   * MSE: 4108577.44 
   * MAE: 1504.11 
   * R2-score: 0.93 
   * Feature Importance: ([ 1,  9,  8,  7,  1,  1,  6,  1,  1,  1,  1,  1,  1,  1,  1,  1,  1, 3, 4, 5, 1, 10, 1, 2, 11]) 

Dependencies 

   * Python 
   * Libraries: pandas, numpy, seaborn, matplotlib, sklearn, warnings. 

Contributing 

Contributions are welcome! If you find any issues or have suggestions, please open an issue or submit a pull request. 
