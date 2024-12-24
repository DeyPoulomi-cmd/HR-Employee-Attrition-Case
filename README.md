# HR Employee Attrition Prediction

This repository focuses on predicting employee attrition within an organization using advanced machine learning techniques. By analyzing employee data, the project aims to provide actionable insights to improve retention strategies and enhance workplace satisfaction.

---

## Problem Statement

Employee attrition is a critical challenge for organizations, leading to increased costs and disruptions. Understanding the factors driving attrition enables businesses to design strategies to retain talent effectively.

---

## Objective

1. Predict whether an employee is likely to leave the organization.
2. Identify the key factors contributing to employee attrition.
3. Provide actionable recommendations to improve retention.

---

## Features of the Project

1. **Data Analysis**:
   - Explored trends in employee demographics, job satisfaction, and performance metrics.
   - Visualized correlations between features such as salary hikes, job level, and attrition rates.

2. **Preprocessing Pipeline**:
   - Handled missing values and outliers in the dataset.
   - Encoded categorical variables such as department and job role.
   - Scaled numerical features for better model performance.

3. **Modeling**:
   - Implemented classification models like Decision Trees, Random Forest, and Logistic Regression.
   - Fine-tuned hyperparameters to maximize prediction accuracy.
   - Achieved an accuracy of 90% using Random Forest, outperforming other models.

4. **Evaluation**:
   - Used metrics like precision, recall, F1-score, and ROC-AUC to assess model effectiveness.

---

## Insights and Learnings

1. **What did I learn?**
   - Employees with low job satisfaction and high overtime hours are more likely to leave.
   - Significant predictors include job role, work-life balance, and salary hikes.
   - Gained experience in applying machine learning to workforce analytics.

2. **What did I try out?**
   - Explored multiple algorithms, including Logistic Regression and ensemble methods.
   - Conducted feature importance analysis to identify key drivers of attrition.
   - Experimented with SMOTE to address class imbalance.

3. **What worked and why?**
   - Random Forest provided the best results due to its ability to handle complex feature interactions.
   - Preprocessing steps like scaling and encoding ensured consistent data inputs.
   - Hyperparameter tuning improved model performance and generalization.

4. **Recommendations for the Business Counterpart**:
   - Focus on improving work-life balance and addressing high overtime for at-risk employees.
   - Provide targeted career development opportunities to employees in critical roles.
   - Regularly monitor workforce data and update predictive models to adapt to changing trends.

---

## Dataset

The dataset contains the following key attributes:
- **Age**: Employee age.
- **JobSatisfaction**: Level of job satisfaction.
- **WorkLifeBalance**: Work-life balance rating.
- **MonthlyIncome**: Monthly salary.
- **OverTime**: Whether the employee works overtime (Yes/No).
- **YearsAtCompany**: Number of years with the company.
- **Attrition**: Target variable (Yes = Left, No = Stayed).

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/username/hr-attrition-prediction.git
   ```

2. Navigate to the project directory:
   ```bash
   cd hr-attrition-prediction
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## Usage

1. Run the Jupyter Notebook to explore the data and train models:
   ```bash
   jupyter notebook HR_Attrition_Prediction.ipynb
   ```

2. Evaluate the trained model:
   ```python
   from sklearn.metrics import classification_report

   y_pred = model.predict(X_test)
   print(classification_report(y_test, y_pred))
   ```

---

## Results

- **Accuracy**: 90%
- **Key Predictors**: Job Role, Work-Life Balance, Overtime
- **Impact**: Enhanced ability to identify at-risk employees and design targeted retention strategies.

---

## Recommendations

1. Focus on improving work-life balance and reducing overtime for at-risk employees.
2. Offer tailored career development plans for employees in critical job roles.
3. Regularly update workforce data and predictive models to maintain accuracy.

---

## Contributing

Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-branch
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-branch
   ```
5. Open a pull request.

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Acknowledgments

- The dataset is sourced from IBM HR Analytics.
- Thanks to the data science community for valuable resources and inspiration.

---

Thank you for exploring this project! If you have any questions or suggestions, feel free to reach out.
