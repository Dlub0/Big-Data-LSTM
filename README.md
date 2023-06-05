# Big-Data-LSTM

When changing files not your own, please first create a new branch and a pull request and set the file owner as Reviewer for approval.

## Final Concept and Motivation

## Must, could and limitations

### Must 

* Generate a "twinned" data set of artifical Glucose Levels with affecting factors of eating, activity, and insulin application.

* Use visualization tools, such as matplotlib or seaborn, to visualize the time series data and gain insights into the patterns and trends.

* Preprocess the data to clean and filter out some noise or irrelevant information.

* Preprocess the data to ensure that it is in a suitable format for the LSTM model, such as normalizing or scaling the data.

* Split the data into training, validation, and testing sets to evaluate the performance of your model on new data.

* Train the LSTM model.

* Experiment with different model architecture, e.g. stacking layers horizontally or vertically, how many hidden layers/ neurons, etc. 

* Experiment with different window sizes and strides to determine the optimal values that balance the trade-off between capturing sufficient temporal information and avoiding overfitting.

* Experiment with size of prediction to see how far in the future the model can make realistic predictions, do any strange effects/ patterns emerge?

* Apply model to actual dataset, compare results with the artificially generated.

### Could:

* Use appropriate data filtering techniques to remove outliers or anomalies in the data that may affect the performance of your model.

* Evaluate the model's performance using appropriate metrics, such as mean squared error or R-squared, to determine its accuracy and generalization ability. 

* Experiment with different hyperparameters, such as the number of hidden layers or the learning rate, to optimize the performance of your model.

* Use data augmentation techniques, such as adding noise or shifting the time series, to increase the amount of training data and improve the robustness of your model.

* Consider the impact of windowing on the performance of your model, such as the potential loss of information at the boundaries of each window, and take appropriate steps to mitigate these effects.

### Limitations:

* Lack of context: Without additional information about the patients, such as their age, gender, medical history, or lifestyle factors, it may be challenging to account for confounding variables that could affect the glucose monitoring time series.

* Limited sample size: Depending on the size of the dataset, it may be difficult to generalize the results of the project to a larger patient population or to different healthcare settings.

* Missing data: The dataset may contain missing or incomplete glucose measurements, which could affect the accuracy of the model and make it challenging to analyze the time series data. -> This should be ignored.

* Technical limitations: Depending on the computational resources available, it may be challenging to train and evaluate complex machine learning models, such as LSTMs, on large time series datasets.

## Resource Links and Tutorials

Inspiration: [Blood Gluncose Predictions](https://ieeexplore.ieee.org/document/8723121)

Dataset : [Inpatient Evaluation of an Automated Closed-Loop Control-to-Range System (CTR)] (https://public.jaeb.org/datasets/diabetes)
