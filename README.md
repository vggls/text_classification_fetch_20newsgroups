## Dataset
- Training data: 11314 texts
- Test data: 7532 texts
- Unbalanced datasets (see Report.pdf for details)
- Allocated into 20 categories
- Dataset source: https://scikit-learn.org/0.19/datasets/twenty_newsgroups.html

## Workflow - Architecture

<p float="center">
     <img src="https://github.com/vggls/text_classification_fetch_20newsgroups/assets/55101427/34a6c0dc-8f13-42e1-ad20-8980e33370d6.png" height="470" width="800" />
</p>

## Test Results

    Model  | Accuracy | Precision(*) | Recall(*) | F1-Score(*) |
    ------------------------------------------------------------
    SVM    |   0.66   |     0.68     |    0.66   |    0.66     |
    BiLSTM |   0.67   |     0.68     |    0.67   |    0.67     |

    (*) weighted metrics
