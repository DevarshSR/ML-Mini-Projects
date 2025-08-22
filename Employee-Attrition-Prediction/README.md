# Employee Attrition Prediction

## Overview

This project demonstrates a machine learning solution for predicting employee attrition using a Logistic Regression model. The goal is to help organizations identify employees who are likely to leave, enabling proactive retention strategies and improved workforce planning.

## Problem Statement

Employee attrition is a critical challenge for organizations, impacting productivity, morale, and costs. By leveraging historical HR data, this project builds a predictive model to classify employees as likely to stay or leave, supporting data-driven decision-making in human resources.

## Dataset

- **Source:** IBM HR Analytics Employee Attrition & Performance
- **File:** `data/WA_Fn-UseC_-HR-Employee-Attrition.csv`
- **Features:** Demographic, job-related, and performance attributes
- **Target:** Attrition (Yes/No)

## Solution Approach

1. **Data Preprocessing:**
   - Handle missing values
   - Encode categorical variables
   - Feature scaling
2. **Model Building:**
   - Train/test split
   - Logistic Regression model
3. **Evaluation:**
   - Accuracy score
   - Predict on custom employee profiles

## Project Structure

```
├── Employee_Attrition_Prediction.ipynb  # Main notebook
├── requirements.txt                     # Python dependencies
├── data/
│   └── WA_Fn-UseC_-HR-Employee-Attrition.csv  # Dataset
```

## Usage

1. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
2. **Run the notebook:**
   - Open `Employee_Attrition_Prediction.ipynb` in Jupyter or VS Code
   - Execute cells sequentially
3. **Customize predictions:**
   - Modify employee profiles in the notebook to test attrition predictions

## Key Technologies

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## Results

- Achieved high accuracy in predicting employee attrition
- Model can be used for real-time HR analytics and decision support

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for improvements, bug fixes, or new features.

## License

This project is licensed under the MIT License.

## Author

- Devarsh S R


---

For questions or support, please contact the author or open an issue in the repository.
