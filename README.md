# neural-network-challenge-1

# Student Loan Risk with Deep Learning

This project focuses on using deep learning techniques to predict student loan repayment success based on various features. The project involves preprocessing the data, creating a neural network model, training the model, evaluating its performance, and making predictions.

## Steps to Run the Code

1. Clone the repository to your local machine.
2. Install the required dependencies by running `pip install -r requirements.txt`.
3. Run the code in `student_loan_deep_learning.py` to preprocess the data, create and train the neural network model, and evaluate its performance.
4. The model will be saved as `student_loans.keras`.
5. You can then reload the saved model and make predictions on new data.

## Data

The data used in this project is sourced from the `student-loans.csv` file, which contains columns such as payment history, location parameter, stem degree score, GPA ranking, alumni success, and more. These columns are used to define the features and target variables for the neural network model.

## Model Performance

After training the model and evaluating its performance on the test data, the model achieved an accuracy of 76% in predicting loan repayment success. The classification report shows precision, recall, and F1-score for each class, providing insights into the model's performance.

## Conclusion

This project demonstrates the application of deep learning techniques to predict student loan repayment success. By following the steps outlined in the code and README.md file, you can replicate the process and analyze the performance of the neural network model.
