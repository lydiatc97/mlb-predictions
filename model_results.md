## Baseline (All Features)

### Randomized Selection of Training and Testing Datasets Using `train_test_split`

#### Logistic Regression:

Accuracy Score: 0.5640096618357487

Confusion Matrix:

```
True Positive(TP) =  17
False Positive(FP) =  11
True Negative(TN) =  7
False Negative(FN) =  6
```

Classification Report:
```
              precision    recall  f1-score   support

           0       0.54      0.39      0.45        18
           1       0.61      0.74      0.67        23

    accuracy                           0.59        41
   macro avg       0.57      0.56      0.56        41
weighted avg       0.58      0.59      0.57        41
```

#### XGBoost:

Accuracy Score: 0.5483091787439613

Confusion Matrix:

```
True Positive(TP) =  15
False Positive(FP) =  10
True Negative(TN) =  8
False Negative(FN) =  8
```

Classification Report:
```
              precision    recall  f1-score   support

           0       0.50      0.44      0.47        18
           1       0.60      0.65      0.63        23

    accuracy                           0.56        41
   macro avg       0.55      0.55      0.55        41
weighted avg       0.56      0.56      0.56        41
```

### Splitting Training and Testing Sets Chronologically With List Indexing

#### Logistic Regression:

Accuracy Score: 0.5416666666666667

Confusion Matrix:

```
True Positive(TP) =  23
False Positive(FP) =  14
True Negative(TN) =  2
False Negative(FN) =  1
```

Classification Report:

```
              precision    recall  f1-score   support

           0       0.67      0.12      0.21        16
           1       0.62      0.96      0.75        24

    accuracy                           0.62        40
   macro avg       0.64      0.54      0.48        40
weighted avg       0.64      0.62      0.54        40
```

#### XGBoost:

Accuracy Score: 0.4791666666666667

```
True Positive(TP) =  23
False Positive(FP) =  16
True Negative(TN) =  0
False Negative(FN) =  1
```

Classification Report:

```
              precision    recall  f1-score   support

           0       0.00      0.00      0.00        16
           1       0.59      0.96      0.73        24

    accuracy                           0.57        40
   macro avg       0.29      0.48      0.37        40
weighted avg       0.35      0.57      0.44        40
```

---



## No Home/Away Feature

### Randomized Selection of Training and Testing Datasets Using `train_test_split`

#### Logistic Regression:

Accuracy Score: 0.4867149758454106

Confusion Matrix:

```
True Positive(TP) =  16
False Positive(FP) =  13
True Negative(TN) =  5
False Negative(FN) =  7
```

Classification Report:

```
              precision    recall  f1-score   support

           0       0.42      0.28      0.33        18
           1       0.55      0.70      0.62        23

    accuracy                           0.51        41
   macro avg       0.48      0.49      0.47        41
weighted avg       0.49      0.51      0.49        41
```

#### XGBoost:

Accuracy Score: 0.6341463414634146

Confusion Matrix:

```
True Positive(TP) =  19
False Positive(FP) =  11
True Negative(TN) =  7
False Negative(FN) =  4
```

Classification Report:
```
              precision    recall  f1-score   support

           0       0.64      0.39      0.48        18
           1       0.63      0.83      0.72        23

    accuracy                           0.63        41
   macro avg       0.63      0.61      0.60        41
weighted avg       0.63      0.63      0.61        41
```

### Splitting Training and Testing Sets Chronologically With List Indexing

#### Logistic Regression:

Accuracy Score: 0.5416666666666667

Confusion Matrix:

```
True Positive(TP) =  23
False Positive(FP) =  14
True Negative(TN) =  2
False Negative(FN) =  1
```

Classification Report:
```
              precision    recall  f1-score   support

           0       0.67      0.12      0.21        16
           1       0.62      0.96      0.75        24

    accuracy                           0.62        40
   macro avg       0.64      0.54      0.48        40
weighted avg       0.64      0.62      0.54        40
```

#### XGBoost:

Accuracy Score: 0.4895833333333333

Confusion Matrix:
```
True Positive(TP) =  22
False Positive(FP) =  15
True Negative(TN) =  1
False Negative(FN) =  2
```

Classification Report:
```
              precision    recall  f1-score   support

           0       0.33      0.06      0.11        16
           1       0.59      0.92      0.72        24

    accuracy                           0.57        40
   macro avg       0.46      0.49      0.41        40
weighted avg       0.49      0.57      0.47        40
```

---

## No Day/Night Feature

### Randomized Selection of Training and Testing Datasets Using `train_test_split`

#### Logistic Regression:

Accuracy Score: 0.4867149758454106

Confusion Matrix:

```
True Positive(TP) =  16
False Positive(FP) =  13
True Negative(TN) =  5
False Negative(FN) =  7
```

Classification Report:
```
              precision    recall  f1-score   support

           0       0.42      0.28      0.33        18
           1       0.55      0.70      0.62        23

    accuracy                           0.51        41
   macro avg       0.48      0.49      0.47        41
weighted avg       0.49      0.51      0.49        41
```

#### XGBoost:

Accuracy Score: 0.4878048780487805

Confusion Matrix:
```
True Positive(TP) =  13
False Positive(FP) =  11
True Negative(TN) =  7
False Negative(FN) =  10
```

Classification Report:
```
              precision    recall  f1-score   support

           0       0.41      0.39      0.40        18
           1       0.54      0.57      0.55        23

    accuracy                           0.49        41
   macro avg       0.48      0.48      0.48        41
weighted avg       0.48      0.49      0.49        41
```

### Splitting Training and Testing Sets Chronologically With List Indexing

#### Logistic Regression:

Accuracy Score: 0.5416666666666667

Confusion Matrix: 
```
True Positive(TP) =  23
False Positive(FP) =  14
True Negative(TN) =  2
False Negative(FN) =  1
```

Classification Report:
```
              precision    recall  f1-score   support

           0       0.67      0.12      0.21        16
           1       0.62      0.96      0.75        24

    accuracy                           0.62        40
   macro avg       0.64      0.54      0.48        40
weighted avg       0.64      0.62      0.54        40
```

#### XGBoost:

Accuracy Score: 0.5416666666666667

Confusion Matrix:
```
True Positive(TP) =  23
False Positive(FP) =  14
True Negative(TN) =  2
False Negative(FN) =  1
```

Classification Report:
```
              precision    recall  f1-score   support

           0       0.67      0.12      0.21        16
           1       0.62      0.96      0.75        24

    accuracy                           0.62        40
   macro avg       0.64      0.54      0.48        40
weighted avg       0.64      0.62      0.54        40
```


---

## No Rank Feature

### Randomized Selection of Training and Testing Datasets Using `train_test_split`

#### Logistic Regression:

Accuracy Score: 0.5640096618357487

Confusion Matrix: 
```
True Positive(TP) =  17
False Positive(FP) =  11
True Negative(TN) =  7
False Negative(FN) =  6
```

Classification Report:
```
              precision    recall  f1-score   support

           0       0.54      0.39      0.45        18
           1       0.61      0.74      0.67        23

    accuracy                           0.59        41
   macro avg       0.57      0.56      0.56        41
weighted avg       0.58      0.59      0.57        41
```

#### XGBoost:

Accuracy Score: 0.5121951219512195

Confusion Matrix:
```
True Positive(TP) =  15
False Positive(FP) =  12
True Negative(TN) =  6
False Negative(FN) =  8
```

Classification Report:
```
              precision    recall  f1-score   support

           0       0.43      0.33      0.38        18
           1       0.56      0.65      0.60        23

    accuracy                           0.51        41
   macro avg       0.49      0.49      0.49        41
weighted avg       0.50      0.51      0.50        41
```

### Splitting Training and Testing Sets Chronologically With List Indexing

#### Logistic Regression:

Accuracy Score: 0.5416666666666667

Confusion Matrix:
```
True Positive(TP) =  23
False Positive(FP) =  14
True Negative(TN) =  2
False Negative(FN) =  1
```

Classification Report:
```
              precision    recall  f1-score   support

           0       0.67      0.12      0.21        16
           1       0.62      0.96      0.75        24

    accuracy                           0.62        40
   macro avg       0.64      0.54      0.48        40
weighted avg       0.64      0.62      0.54        40
```

#### XGBoost:

Accuracy Score: 0.40625

Confusion Matrix:
```
True Positive(TP) =  18
False Positive(FP) =  15
True Negative(TN) =  1
False Negative(FN) =  6
```

Classification Report:
```
              precision    recall  f1-score   support

           0       0.14      0.06      0.09        16
           1       0.55      0.75      0.63        24

    accuracy                           0.48        40
   macro avg       0.34      0.41      0.36        40
weighted avg       0.38      0.47      0.41        40
```
