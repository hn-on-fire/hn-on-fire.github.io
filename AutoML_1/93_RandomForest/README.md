# Summary of 93_RandomForest

[<< Go back](../README.md)


## Random Forest
- **n_jobs**: -1
- **criterion**: gini
- **max_features**: 0.7
- **min_samples_split**: 50
- **max_depth**: 7
- **eval_metric_name**: auc
- **explain_level**: 0

## Validation
 - **validation_type**: split
 - **train_ratio**: 0.8
 - **shuffle**: True
 - **stratify**: True

## Optimized metric
auc

## Training time

2.7 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.3225   |  nan        |
| auc       | 0.900044 |  nan        |
| f1        | 0.788655 |    0.576417 |
| accuracy  | 0.832836 |    0.589153 |
| precision | 0.862745 |    0.706474 |
| recall    | 1        |    0        |
| mcc       | 0.690147 |    0.479369 |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.3225   |  nan        |
| auc       | 0.900044 |  nan        |
| f1        | 0.787476 |    0.589153 |
| accuracy  | 0.832836 |    0.589153 |
| precision | 0.679214 |    0.589153 |
| recall    | 0.936795 |    0.589153 |
| mcc       | 0.678442 |    0.589153 |


## Confusion matrix (at threshold=0.589153)
|                     |   Predicted as APPROVED |   Predicted as DECLINED |
|:--------------------|------------------------:|------------------------:|
| Labeled as APPROVED |                     701 |                     196 |
| Labeled as DECLINED |                      28 |                     415 |

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