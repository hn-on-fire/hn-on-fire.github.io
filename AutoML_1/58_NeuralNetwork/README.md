# Summary of 58_NeuralNetwork

[<< Go back](../README.md)


## Neural Network
- **n_jobs**: -1
- **dense_1_size**: 16
- **dense_2_size**: 16
- **learning_rate**: 0.05
- **explain_level**: 0

## Validation
 - **validation_type**: split
 - **train_ratio**: 0.8
 - **shuffle**: True
 - **stratify**: True

## Optimized metric
auc

## Training time

2.5 seconds

## Metric details
|           |    score |      threshold |
|:----------|---------:|---------------:|
| logloss   | 0.341355 | nan            |
| auc       | 0.879064 | nan            |
| f1        | 0.779152 |   0.371002     |
| accuracy  | 0.813433 |   0.371002     |
| precision | 0.75     |   0.677173     |
| recall    | 1        |   3.43031e-224 |
| mcc       | 0.676756 |   0.371002     |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.341355 |  nan        |
| auc       | 0.879064 |  nan        |
| f1        | 0.779152 |    0.371002 |
| accuracy  | 0.813433 |    0.371002 |
| precision | 0.640058 |    0.371002 |
| recall    | 0.995485 |    0.371002 |
| mcc       | 0.676756 |    0.371002 |


## Confusion matrix (at threshold=0.371002)
|                     |   Predicted as APPROVED |   Predicted as DECLINED |
|:--------------------|------------------------:|------------------------:|
| Labeled as APPROVED |                     649 |                     248 |
| Labeled as DECLINED |                       2 |                     441 |

## Learning curves
![Learning curves](learning_curves.png)
## Confusion Matrix

![Confusion Matrix](confusion_matrix.png)


## Normalized Confusion Matrix

![Normalized Confusion Matrix](confusion_matrix_normalized.png)


## ROC Curve

![ROC Curve](roc_curve.png)


## Kolmogorov-Smirnov Statistic

![Kolmogorov-Smirnov Statistic](ks_statistic.png)


## Precision-Recall Curve

![Precision-Recall Curve](precision_recall_curve.png)


## Calibration Curve

![Calibration Curve](calibration_curve_curve.png)


## Cumulative Gains Curve

![Cumulative Gains Curve](cumulative_gains_curve.png)


## Lift Curve

![Lift Curve](lift_curve.png)



[<< Go back](../README.md)
