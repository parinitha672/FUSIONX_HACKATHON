# FUSIONX_HACKATHON
# Fraud Detection Hackathon Project
This project uses train and test datasets to detect fraudulent transactions using machine learning.

## Prerequisites
- Python 3.x
- Jupyter Notebook
- Libraries: pandas, scikit-learn, matplotlib, seaborn, openpyxl
- Datasets: train_data.csv.xlsx and test_data.csv.xlsx

- ## Installation
1. Clone or download this project folder.
2. Install dependencies:
   ```bash
   pip install pandas scikit-learn matplotlib seaborn openpyxl
   Jupyter Notebook

   ### 5. Running the Project
```markdown
## Running the Project
1. Place train_data.csv.xlsx and test_data.csv.xlsx in the project folder.
2. Open FraudDetection.ipynb in Jupyter Notebook.
3. Run cells in order:
   - Step 1–7: Exploratory Data Analysis (EDA)
   - Preprocessing: Encode categorical features
   - Model Training: RandomForest with balanced weights
   - Evaluation: Confusion matrix, classification report, ROC-AUC
   - Visualization: Feature importance plot
   - Save predictions: Add predicted fraud labels to test dataset

## Outputs
- Dataset preview
- EDA plots (histograms, correlation heatmap)
- Confusion matrix and classification report
- ROC-AUC score
- Feature importance visualization
- Test dataset with predicted fraud labels

## Folder Structure
project/
│── FraudDetection.ipynb        # Jupyter Notebook
│── train_data.csv.xlsx          # Training dataset
│── test_data.csv.xlsx           # Testing dataset
│── README.md                    # Instructions
│── screenshots/                 # Output screenshots


