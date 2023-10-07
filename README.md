
# Term Deposit Subscription Prediction

## Problem Statement

Your client is a retail banking institution where term deposits are a major source of income. Term deposits involve cash investments held at the bank for an agreed interest rate over a fixed period. The bank conducts various marketing campaigns, including telephonic ones, to sell term deposits. Telephonic marketing campaigns are effective but require substantial investments. Hence, it's crucial to identify potential customers likely to convert beforehand, allowing targeted outreach via calls. The task is to predict whether a client will subscribe to a term deposit based on provided client and call data.

## Dataset

You are provided with the following files:

1. **train.csv**: Training dataset containing client details and target variable "subscribed." Use this for model training.
2. **test.csv**: Test dataset to predict new clients' subscriptions using the trained model.

### Data Dictionary

- **ID**: Unique client ID
- **age**: Age of the client
- **job**: Type of job
- **marital**: Marital status of the client
- **education**: Education level
- **default**: Credit in default
- **housing**: Housing loan
- **loan**: Personal loan
- **contact**: Type of communication
- **month**: Contact month
- **day_of_week**: Day of the week of contact
- **duration**: Contact duration
- **campaign**: Number of contacts performed during this campaign
- **pdays**: Number of days passed since the client was last contacted
- **previous**: Number of contacts performed before this campaign
- **poutcome**: Outcome of the previous marketing campaign
- **subscribed**: Target variable - whether the client subscribed to a term deposit (yes/no)

## Approach

1. **Data Exploration**: Understand the dataset, handle missing values, and explore feature distributions.
2. **Feature Engineering**: Extract useful features, convert categorical variables into numerical forms, and handle any outliers.
3. **Model Selection**: Choose appropriate classification models (e.g., Logistic Regression, Random Forest, Gradient Boosting) to predict the binary target variable.
4. **Model Training**: Use the training dataset to train the selected models.
5. **Model Evaluation**: Evaluate model performance using accuracy as the metric. Perform cross-validation to ensure the model's robustness.
6. **Prediction**: Use the trained model to make predictions on the test dataset.
7. **Submission**: Save the predictions in the required format and submit the solution.

## How to Use

1. **Clone the Repository**: Clone this repository to your local machine using `git clone https://github.com/your-username/term-deposit-subscription-prediction.git`.
2. **Requirements**: Make sure you have Python installed. Use `pip install -r requirements.txt` to install the necessary packages.
3. **Data**: Place the provided `train.csv` and `test.csv` files in the `data` directory.
4. **Notebook**: Use the Jupyter Notebook `term_deposit_prediction.ipynb` to explore the data, train the model, and make predictions.
5. **Predictions**: Save the final predictions in a CSV file named `submissions.csv`.
6. **Readme**: Update this README file with specific instructions for the solution and upload it to your GitHub repository.
7. **Submission**: Submit the predictions file (`submissions.csv`) on the provided solution checker according to the instructions provided.

Feel free to customize the approach and code to improve model performance and achieve better accuracy.

Best of luck with your solution! If you have any questions or need further assistance, please feel free to reach out.
