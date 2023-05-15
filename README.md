# Big-Data-LSTM

When changing files not your own, please first create a new branch and a pull request and set the file owner as Reviewer for approval.

## Final Concept and Motivation

## Must, could and limitations

### Must 

* Preprocess the data to clean and filter out any noise or irrelevant information that may affect the accuracy of your model.

* Preprocess the data to ensure that it is in a suitable format for your LSTM model, such as normalizing or scaling the data.

* Use appropriate data filtering techniques to remove outliers or anomalies in the data that may affect the performance of your model.

* Split the data into training, validation, and testing sets to evaluate the performance of your model on new data.

* Evaluate the model's performance using appropriate metrics, such as mean squared error or R-squared, to determine its accuracy and generalization ability.

* Train the LSTM model on a sufficient amount of data to ensure that it can learn the patterns and trends in the glucose monitoring time series.

* Experiment with different window sizes and strides to determine the optimal values that balance the trade-off between capturing sufficient temporal information and avoiding overfitting.

### Could:

* Use visualization tools, such as matplotlib or seaborn, to visualize the time series data and gain insights into the patterns and trends.

* Explore different types of recurrent neural networks, such as GRU or BiLSTM, to compare their performance with LSTM.

* Experiment with different hyperparameters, such as the number of hidden layers or the learning rate, to optimize the performance of your model.

* Compare the performance of the LSTM model with other machine learning models, such as linear regression or decision trees, to determine the most appropriate approach for the task.

* Use data augmentation techniques, such as adding noise or shifting the time series, to increase the amount of training data and improve the robustness of your model.

* Consider the impact of windowing on the performance of your model, such as the potential loss of information at the boundaries of each window, and take appropriate steps to mitigate these effects.

### Limitations:

* Lack of context: Without additional information about the patients, such as their age, gender, medical history, or lifestyle factors, it may be challenging to account for confounding variables that could affect the glucose monitoring time series.

* Limited sample size: Depending on the size of the dataset, it may be difficult to generalize the results of the project to a larger patient population or to different healthcare settings.

* Missing data: The dataset may contain missing or incomplete glucose measurements, which could affect the accuracy of the model and make it challenging to analyze the time series data.

* Technical limitations: Depending on the computational resources available, it may be challenging to train and evaluate complex machine learning models, such as LSTMs, on large time series datasets.

## Resource Links and Tutorials

Inspiration: [Blood Gluncose Predictions](https://ieeexplore.ieee.org/document/8723121)

Dataset : [Inpatient Evaluation of an Automated Closed-Loop Control-to-Range System (CTR)] (https://public.jaeb.org/datasets/diabetes)
