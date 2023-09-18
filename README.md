## Dataset
- Training data: 11314 texts
- Test data: 7532 texts
- Unbalanced datasets (see Report.pdf for details)
- Allocated into 20 categories
- Dataset source: https://scikit-learn.org/0.19/datasets/twenty_newsgroups.html

## Workflow - Architecture

(to be inserted)

## Test Results

    Model  | Accuracy | Precision(*) | Recall(*) | F1-Score(*) |
    ------------------------------------------------------------
    SVM    |   0.66   |     0.68     |    0.66   |    0.66     |
    BiLSTM |   0.67   |     0.68     |    0.67   |    0.67     |

    (*) weighted metrics
