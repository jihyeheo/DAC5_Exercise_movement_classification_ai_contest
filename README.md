# DAC5_Exercise_movement_classification_ai_contest(20210110~20210126)

- This project is a classification model that predicts exercise status by viewing a graph drawn over 600 seconds.
- Machine Learning : RandomForest.K-NN
- Deep Learning : ANN, RNN, LSTM, GRU, CNN

[[Interim report]](https://github.com/jihyeheo/DAC5_Exercise_movement_classification_ai_contest/blob/main/Intermediate_Report_Exercise_movement_classifcation_.pdf) | [[Code]](https://github.com/jihyeheo/DAC5_Exercise_movement_classification_ai_contest/blob/main/Intermediate_Report.ipynb)
# Data Amalysis club : First personal assignment

### [Motivation for topic selection ]
I wanted to analyze data that is not two-dimensional, and I wanted to deal with time series data analysis because it is my first time.(2차원이 아닌 데이터를 다루어서 분석을 해보고 싶었고 시계열 데이터 분석은 처음이어서 다루어보고 싶었다.)

### [Data]
Sensor data using 3rd accelerometer and 3-axis gyroscope(3축 가속도계와 3축 자이로스코프를 활용한 센서 데이터)

train_feature : id, acc_x,y,z, gy_x,y,z <br>
train_labels : id, labels, labes_desc <br>
test_feature : same train_feature<br>
sample_submission : Predicted value to submit<br>

