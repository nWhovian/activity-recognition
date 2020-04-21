# Human Activity Recognition using mobile sensors

In my algorithm, I used the previously pre-processed and divided into train/test sections data set and created three models using the scikit-learn library. Then I have tuned the hyper-parameters of these models using the Grid-Search-CV and came up with the best set of parameters for each model. Finally, I have evaluated each model on the test data set and created a confusion matrix for it.

## Results

```
sgd average accuracy: 95.374
log_reg average accuracy: 96.132
svm average accuracy: 95.792
```
```
sgd average exec time: 70.502 s
log_reg average exec time: 144.65 s
svm average exec time: 75.824 s
```

