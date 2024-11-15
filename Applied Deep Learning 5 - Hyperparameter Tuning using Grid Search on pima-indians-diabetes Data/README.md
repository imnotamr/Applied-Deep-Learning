# Diabetes Prediction with Hyperparameter Tuning

This project aims to develop a predictive model for diabetes diagnosis using the Pima Indians Diabetes dataset. We explore hyperparameter tuning techniques to enhance model performance, applying grid search to optimize parameters.

## Dataset
The dataset contains 768 records of patient information, each with the following attributes:
1. **Pregnancies**: Number of times pregnant
2. **Glucose**: Plasma glucose concentration after a 2-hour test
3. **BloodPressure**: Diastolic blood pressure (mm Hg)
4. **SkinThickness**: Triceps skin fold thickness (mm)
5. **Insulin**: 2-hour serum insulin (mu U/ml)
6. **BMI**: Body mass index (kg/m²)
7. **DiabetesPedigreeFunction**: A function scoring the likelihood of diabetes based on family history
8. **Age**: Patient age (years)
9. **Outcome**: Diabetes diagnosis (0 = non-diabetic, 1 = diabetic)

## Project Workflow
1. **Data Preprocessing**: Data normalization and handling of missing values.
2. **Model Building**: Creation of a baseline classification model for diabetes prediction.
3. **Hyperparameter Tuning**: Using Grid Search to fine-tune model parameters and improve accuracy.
4. **Evaluation**: Model evaluation using accuracy, precision, and recall metrics.

## Usage
1. Load the dataset and notebook.
2. Run each cell in the notebook to preprocess the data, build the model, and perform hyperparameter tuning.
3. Evaluate the results and identify the optimal model configuration for diabetes prediction.

## Requirements
- Python 3.x
- Scikit-learn
- Pandas
- Numpy
- Matplotlib (for visualizations, if included)

## Results
The notebook concludes with the optimal hyperparameters found and evaluates model performance on the test data, providing insights on model effectiveness for diabetes prediction.
