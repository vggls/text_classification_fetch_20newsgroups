## Dataset
- Training data: 11314 texts
- Test data: 7532 texts
- Unbalanced datasets (see Report.pdf for details)
- Allocated into 20 categories
- Dataset source: https://scikit-learn.org/0.19/datasets/twenty_newsgroups.html

## Workflow

<p float="center">
     <img src="https://github.com/vggls/text_classification_fetch_20newsgroups/assets/55101427/701ce548-bbff-481a-80c0-e6ed5ef78d1c.png" height="475" width="800" />
</p>

<p float="center">
     <img src="https://github.com/vggls/text_classification_fetch_20newsgroups/assets/55101427/8b66982d-4481-420b-9ad8-d8d050657bca.png" height="350" width="900" />
</p>

## Test Results

    Model  | Accuracy | Precision(*) | Recall(*) | F1-Score(*) |
    ------------------------------------------------------------
    SVM    |   0.66   |     0.68     |    0.66   |    0.66     |
    BiLSTM |   0.67   |     0.68     |    0.67   |    0.67     |

    (*) weighted metrics
