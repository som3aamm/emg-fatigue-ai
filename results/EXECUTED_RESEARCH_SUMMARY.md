# Executed Results and Methods Audit

Participants evaluated: 13
Matched recordings: 156
Labeled windows: 11692

## Held-out participant model summary
| model                  |   mean_subject_macro_f1 |   sd_subject_macro_f1 |   mean_balanced_accuracy |   mean_precision |   mean_recall |   mean_ms_per_window |   tested_subjects |
|:-----------------------|------------------------:|----------------------:|-------------------------:|-----------------:|--------------:|---------------------:|------------------:|
| hist_gradient_boosting |                0.435359 |             0.0368478 |                 0.462716 |         0.466177 |      0.462716 |          0.0264687   |                13 |
| mlp                    |                0.434387 |             0.0421661 |                 0.460965 |         0.467245 |      0.460965 |          0.00364428  |                13 |
| svm_rbf                |                0.430112 |             0.0524232 |                 0.454369 |         0.473904 |      0.454369 |          0.927439    |                13 |
| random_forest          |                0.422562 |             0.0632827 |                 0.455518 |         0.471834 |      0.455518 |          0.065023    |                13 |
| logistic               |                0.417315 |             0.0530776 |                 0.451532 |         0.463216 |      0.451532 |          0.00363352  |                13 |
| cnn_1d                 |                0.369303 |             0.0753961 |                 0.411032 |         0.412632 |      0.411032 |          0.120402    |                13 |
| cnn_gru                |                0.356895 |             0.0654291 |                 0.392583 |         0.421427 |      0.392583 |          0.448915    |                13 |
| majority               |                0.173742 |             0.0363056 |                 0.333333 |         0.119693 |      0.333333 |          0.000236192 |                13 |

## Important interpretation
Target labels are ordinal self-perceived fatigue assessments.
The calibration study uses labeled target-participant support observations.
Outer held-out participants are disjoint from all training subjects.