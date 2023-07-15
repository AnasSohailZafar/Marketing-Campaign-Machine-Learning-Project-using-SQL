# Marketing Campaign Machine Learning Project

This project focuses on building and evaluating machine learning models to predict customers' likelihood of subscribing to a term deposit in a marketing campaign. The project aims to provide actionable insights and improve decision-making in marketing efforts.

## Table of Contents
- [Project Overview](#project-overview)
- [Getting Started](#getting-started)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [Results and Findings](#results-and-findings)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The marketing campaign dataset contains information about customers, their attributes, and the outcome of the previous marketing campaign. The dataset was used to train and evaluate different machine learning models, including decision trees, support vector machines (SVM), and k-nearest neighbors (KNN).

The project involves several steps:
1. Data preprocessing: Exploratory data analysis, handling missing values, encoding categorical variables, and scaling numerical features.
2. Model selection and training: Building and training decision tree, SVM, and KNN models using appropriate parameters and techniques.
3. Evaluation: Assessing the predictive accuracy, processing time, and ability to estimate class probabilities for each model.
4. Feature Importance: Computing and analyzing the feature importance of the decision tree model.
5. Communication and Critical Thinking: Effectively communicating the results, addressing ethical implications, and considering fairness, accountability, and transparency.

## Getting Started

To get started with this project, follow these steps:

1. Clone the repository: `git clone https://github.com/your-username/marketing-campaign-ml.git`
2. Install the required dependencies (see next section).
3. Run the Jupyter Notebook files in the preferred order to execute the different project steps.

## Dependencies

The project requires the following dependencies:

- Python 3 (https://www.python.org/downloads/)
- Jupyter Notebook (https://jupyter.org/install)
- scikit-learn (https://scikit-learn.org/stable/install.html)
- pandas (https://pandas.pydata.org/getting_started.html)
- numpy (https://numpy.org/install/)
- matplotlib (https://matplotlib.org/stable/users/installing.html)
- pymysql
- json
- SQL
- sys
## Database Setup

To set up the SQL database and import the data, follow these steps:

1. Make sure you have a running SQL database server.
2. Create a new database or use an existing one for this project.
3. Modify the database connection parameters in the code to match your SQL server configuration (host, username, password, database name).
4. Run the provided SQL script to create the necessary table named `predict_marketing_campaign`.
5. Execute the code snippet provided to import the data from the CSV file into the SQL table.



## Usage

The project is organized into Jupyter Notebook file Run the notebook 


The notebook provide detailed explanations, code, and visualizations to guide you through each step of the project.

## Results and Findings

The project's key results and findings include:
- The decision tree model achieved a testing accuracy of 0.9019, outperforming the SVM (0.8845) and KNN (0.8866) models.
- The decision tree model had a processing time of a few seconds, which was faster compared to SVM (2 minutes) and KNN (8 minutes).
- The decision tree model was capable of estimating class probabilities, providing additional insights into the certainty of predictions.
- The feature importance analysis revealed that the most influential features for predicting term deposit subscriptions were "duration" (56.2%), "poutcome_is_success" (26.1%), "housing" (8.3%), and "age" (6.8%).

For more detailed information and analysis, refer to the corresponding Jupyter Notebook files.

## Contributing

Contributions to this project are welcome. If you have any suggestions, improvements, or bug fixes, please create a pull request. For major changes, please open an issue first to discuss the proposed changes.

## License

This project is licensed under the [MIT License](LICENSE). You are free to modify, distribute, and use the code for personal and commercial purposes.

Contact Information
For any questions or suggestions, please feel free to reach out :

Name: Anas Sohail Zafar

Email: anassohailzafar@gmail.com

GitHub: github.com/AnasSohailZafar

Linkedin: www.linkedin.com/in/anas-sohail-zafar123
