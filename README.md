# Risk Level Prediction Model for Life Insurance Applications

## Project Overview
This project aims to streamline the risk assessment process for life insurance applications. By predicting risk levels, this model can assist in calculating premium costs tailored to clients’ profiles. The model is built using machine learning algorithms and evaluates the effectiveness of each through performance metrics such as accuracy and recall.

## Dataset
The dataset used in this project is sourced from [Kaggle’s Prudential Life Insurance Assessment competition](https://www.kaggle.com/competitions/prudential-life-insurance-assessment/data). It includes various variables related to applicants and requires predicting the "Response" variable, which is an ordinal measure of risk with 8 levels.

### Dataset Features
- **Training Data**: Includes features about the applicants along with their respective risk levels (Response variable).
- **Test Data**: Contains similar features without the Response variable.

## Approach
### 1. Data Preprocessing
- Handled missing values and outliers.
- Normalized and standardized features to prepare the data for machine learning algorithms.
- Performed feature selection to reduce dimensionality and improve model efficiency.

### 2. Model Selection
The following machine learning models were explored to predict risk levels:
- **Quadratic Discriminant Analysis (QDA)**
- **AdaBoost Classifier**
- **Random Forest Classifier**

### 3. Evaluation Metrics
The models were evaluated using:
- **Accuracy**: Measures the proportion of correctly classified instances.

## Results
The evaluation results of the models are presented in the notebook. The best-performing model was selected based on the evaluation metrics, with a focus on accuracy.

## Installation and Usage
### Prerequisites
- Python 3.x
- Jupyter Notebook

### Running the Project
1. Clone the repository or download the notebook file.
2. Open the notebook in Jupyter Notebook or Jupyter Lab.
3. Run the cells sequentially to execute the entire workflow.

### File Structure
- `Prudential_Insurance_Classification.ipynb`: The main notebook containing the code and analysis.
- `train.csv`: Training data
- `test.csv`: Testing data
- `README.md`: This file.

## Future Improvements
- Explore additional models such as Gradient Boosting Machines or Neural Networks.
- Incorporate hyperparameter tuning for optimal performance.
- Extend the project to include a web application for real-time predictions.

## Acknowledgments
- **Dataset**: Provided by [Kaggle](https://www.kaggle.com/competitions/prudential-life-insurance-assessment/data).
- **Tools Used**: Python, scikit-learn, pandas, and matplotlib.

## Contact
For any questions or feedback, please contact the project creator:
- **Email**: coeleazar2-c@my.cityu.edu.hk
- **LinkedIn**: https://www.linkedin.com/in/christopher-otniel-eleazar/

---

