# Credit Risk Prediction
ID/X Partners - Data Scientist Internship Project

## Table of Contents
- [About the Project](#about-the-project)
- [Project Goals](#project-goals)
- [Technologies Used](#technologies-used)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Evaluation](#evaluation)
- [Contact](#contact)
- [Acknowledgements](#acknowledgements)

## About the Project
As a Data Scientist intern at ID/X Partners, I developed a machine learning model to predict credit risk for a multifinance company. The goal was to enhance the accuracy of credit risk assessment, optimize business decisions, and reduce potential losses by leveraging data-driven insights.

## Project Goals
- **Develop a Machine Learning Model:** Predict credit risk with high precision.
- **Data Analysis:** Perform comprehensive Data Understanding, Exploratory Data Analysis (EDA), Data Preparation, Data Modeling, and Evaluation.
- **Identify Key Factors:** Determine the factors contributing to credit risk.
- **Optimize Business Decisions:** Enable the client to make informed decisions based on model predictions.

## Technologies Used
- **Programming Languages:** Python & SQL
- **Libraries & Tools:**
  - Data Analysis: Pandas, NumPy
  - Visualization: Matplotlib, Seaborn
  - Machine Learning: Scikit-learn, LightGBM, Extra Trees, Random Forest
  - Others: Jupyter Notebook, Google Colab

## Dataset
- **Name:** Loan Dataset
- **Description:** Contains data on approved and rejected loan applications.
- **Dimensions:**
  - Rows: 466,285
  - Columns: 75
  - Categorical Features: 22
  - Numerical Features: 53
- **Data Dictionary:** [Link to Data Dictionary]

## Installation
1. Clone the Repository
   ```bash
   git clone https://github.com/arknsa/Rakamin-Data-Scientist-IDX-Partners.git
   cd Rakamin-Data-Scientist-IDX-Partners
   ```

2. Create a Virtual Environment
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```


## Results
### Model Performance Metrics:

| Algorithm           | Accuracy | Precision | Recall | F1 Score | ROC AUC |
|---------------------|----------|-----------|--------|----------|---------|
| Logistic Regression | 0.88     | 0.75      | 0.86   | 0.66     | 0.94    |
| Random Forest       | 0.96     | 0.98      | 0.91   | 0.88     | 1.00    |
| Extra Trees         | 0.93     | 0.92      | 0.70   | 0.70     | 0.93    |
| LightGBM            | 0.94     | 0.93      | 0.92   | 0.70     | 0.92    |

### Key Insights:
- **Correlation Analysis:** Identified strong positive and negative correlations between key features.
- **Feature Importance:** Determined the most significant factors influencing credit risk.
- **Model Selection:** Random Forest achieved the highest performance metrics.

## Evaluation
Based on the analysis and model performance, the following recommendations are made:

1. **Deep Business Understanding:** Gain a thorough understanding of the client's business processes to tailor the model effectively.
2. **Integrated Approach:** Combine data analytics, decision-making, risk management, and marketing strategies to provide comprehensive solutions.
3. **Continuous Monitoring:** Regularly update and monitor the model to maintain its accuracy and relevance.

## Contact
- Arkan Syafiq At'taqy
- Surabaya, Indonesia
- 📧 arkanattaqy09@gmail.com
- 🔗 [LinkedIn](https://www.linkedin.com/in/arkan-attaqy/)

## Acknowledgements
- **ID/X Partners:** For providing the opportunity to work on this project.
- **Universitas Airlangga:** For the academic support and resources.
- **Online Communities:** For the invaluable resources and support during the project development.

Thank you for checking out my Credit Risk Prediction project! Feel free to reach out with any questions or feedback.
