# credit-card-behaviour-score

This project aims to predict the likelihood of a "bad flag" for given accounts using a Random Forest Classifier. The dataset is cleaned, preprocessed, and modeled using Python libraries like pandas, scikit-learn, and seaborn.

## Project Structure
- **`Dev_data_to_be_shared.csv`** - Development dataset for training and testing the model.  
- **`validation_data_to_be_shared.csv`** - Validation dataset for generating final predictions.  
- **`Validation_Predictions.csv`** - CSV file containing predicted probabilities for the validation dataset.  

## Requirements
Ensure the following libraries are installed before running the code:
```bash
pip install pandas scikit-learn seaborn matplotlib
```

## Key Features
- Data cleaning and handling missing values.
- Feature selection using Random Forest feature importance.
- Model training and evaluation using accuracy, log loss, PR AUC, and ROC AUC.
- Final prediction generation for the validation dataset.


## Instructions to Run the Code
1. Clone the repository or download the files.
2. Install the required libraries using the command:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Python script to train the model and generate predictions.
4. The output file `Validation_Predictions.csv` will contain predicted probabilities.

## Future Improvements
- Experiment with hyperparameter tuning to improve model accuracy.
- Implement alternative imputation techniques for missing data.
- Add more visualization techniques for better insights.

