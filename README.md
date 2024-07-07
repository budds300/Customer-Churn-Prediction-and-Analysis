# Customer Churn Prediction Project

## Overview

This project aims to predict customer churn in the telecommunications industry using machine learning techniques. By analyzing customer data, we seek to identify factors that influence churn behavior and develop predictive models to anticipate customer attrition. Our goal is to provide actionable insights to improve customer retention strategies and enhance business performance.

## Key Steps

1. **Data Understanding**: 
   - Explored the dataset to understand its structure and contents.
   - Identified features relevant to churn prediction.

2. **Data Preparation**:
   - Handled missing values and inconsistencies.
   - Performed feature engineering to create new variables.
   - Encoded categorical variables for model compatibility.

3. **Model Development**:
   - Selected a range of classification algorithms (e.g., Logistic Regression, Random Forest, XGBoost).
   - Implemented pipelines for data preprocessing and model training.
   - Conducted hyperparameter tuning to optimize model performance.

4. **Model Evaluation**:
   - Evaluated models using metrics such as accuracy, precision, recall, and F1-score.
   - Employed techniques like ROC curves to assess model performance visually.
   - Examined feature importances to understand the drivers of churn.

5. **Insights and Recommendations**:
   - Identified key features influencing churn behavior.
   - Provided recommendations for improving customer retention and service offerings.
   - Outlined actionable insights to drive business decision-making.

## Results

- Logistic Regression emerged as the best-performing model, achieving an accuracy of 80% and demonstrating balanced precision and recall.
- Feature importance analysis revealed that factors such as tenure, contract type, and internet service significantly impact churn behavior.
- Recommendations include enhancing retention strategies for long-tenure customers, improving service quality for fiber optic users, and promoting automatic payment methods for greater stability.

## Future Steps

- Explore additional data sources to enrich the analysis.
- Experiment with advanced machine learning techniques like ensemble methods and neural networks.
- Implement real-time monitoring of churn indicators to enable proactive intervention.

## 💻 Getting Started <a name="getting-started"></a>


To get a local copy up and running, follow these steps.

### Prerequisites

In order to run this project you need:

- Python


### Setup

Clone this repository to your desired folder:


```sh
  cd your-folder
  git clone https://github.com/budds300/Customer-Churn-Prediction-and-Analysis
```
Change into the cloned repository

```sh
  cd Customer-Churn-Prediction-and-Analysis
  
```

Create a virtual environment

```sh

python -m venv env

```

Activate the virtual environment

```sh
    env/Scripts/activate
```
### Install

Here, you need to recursively install the packages in the `requirements.txt` file using the command below 

```sh
   pip install -r requirements.txt
```
### Visualization

![alt text](<Screenshots/customer chur dashboard.png>)


## 👥 Authors <a name="authors"></a>

👩‍💻 **Tamminga Budds**

- GitHub: [GitHub Profile](https://github.com/budds300)

- LinkedIn: [LinkedIn Profile](https://www.linkedin.com/in/tamminga-givondo-n/)

## 🙏 Acknowledgments <a name="acknowledgements"></a>

A big shoutout to my awesome team, Team Maldieves! ♥
Your support, guidance, and collaboration have been invaluable. Thanks for all the help and camaraderie throughout this journey!


## License

This project is licensed under the [MIT License](LICENSE).
