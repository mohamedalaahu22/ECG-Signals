# Abstract

This dataset has been used in exploring heartbeat classification using deep neural network architectures, and observing some of the capabilities of transfer learning on it. The signals correspond to electrocardiogram (ECG) shapes of heartbeats for the normal case and the cases affected by different arrhythmias and myocardial infarction. These signals are preprocessed and segmented, with each segment corresponding to a heartbeat.
# The PTB Diagnostic ECG Database
- Number of Samples: 14552
- Number of Categories: 2
- Data Source: Physionet's PTB Diagnostic Database
## Data Files
This dataset consists of a series of CSV files. Each of these CSV files contain a matrix, with each row representing an example in that portion of the dataset. The final element of each row denotes the class to which that example belongs.

## Datasets
The data used in this project comes from the following sources:

1. **ptbdb_abnormal.csv**
 - **Source:** [(https://www.kaggle.com/datasets/shayanfazeli/heartbeat?select=ptbdb_abnormal.csv)

2. **ptbdb_normal.csv**
   - **Source:** [https://www.kaggle.com/datasets/shayanfazeli/heartbeat?select=ptbdb_normal.csv)

## Features

- Data Loading: Load and preprocess ECG data from CSV files.
- Model Training: Train an CNN model with two SimpleCNN layers.
- Model Evaluation: Evaluate the model using accuracy, precision, recall, F1 score, specificity, and AUC.
- Visualization: Plot the ROC curve to visualize model performance.

## Setup

### Prerequisites

- Python 3.x
- Required libraries: numpy, pandas, scikit-learn, tensorflow, matplotlib

## Results

After training the model, various metrics are computed:

- True Positives (TP): 1134
- True Negatives (TN): 1199
- False Positives (FP): 38
- False Negatives (FN): 56
- Accuracy: 0.961269
- Sensitivity: 0.95294
- Specificity: 0.96928
- Precision: 0.9675767
- F1 Score: 0.96020321
- AUC: 0.990165
