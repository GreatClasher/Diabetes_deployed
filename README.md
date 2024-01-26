# Diabetes Prediction Project

<p align="center">
  <img src="[https://i.postimg.cc/w1WY4jsJ/Screenshot-85.png](https://postimg.cc/2b89BQ5B)" alt="Diabetes Prediction">
</p>

## Overview

This project focuses on predicting diabetes using machine learning. The core functionality is built on a machine learning model, and the user interacts with the model through a Flask web application.

## Features

- **User-Friendly Interface**: An intuitive web form allows users to input relevant health data for predicting diabetes.
- **Machine Learning Prediction**: The application utilizes a pre-trained machine learning model to provide predictions on the likelihood of diabetes based on input parameters.

## How to Use

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/GreaClasher/diabetes-deployed.git
   cd diabetes-prediction
   pip install -r requirements.txt
   python application.py

## Deployment on AWS Beanstalk with CodePipeline

### Seamless Continuous Integration and Deployment

This project is seamlessly deployed on AWS Elastic Beanstalk using AWS CodePipeline, ensuring a smooth and automated continuous integration and deployment process.

#### Elastic Beanstalk Configuration:

The Flask application is expertly deployed on AWS Elastic Beanstalk, with all necessary configurations conveniently stored in the `.ebextensions` folder. This ensures a hassle-free and optimized deployment on the AWS infrastructure.

#### CodePipeline Setup:

AWS CodePipeline takes the lead in automating both the build and deployment processes. The pipeline is finely tuned to monitor changes in the GitHub repository, triggering the deployment pipeline whenever updates are pushed.

- **Source Stage:**
  - Listens attentively to changes in the GitHub repository.

- **Build Stage:**
  - Leverages AWS CodeBuild to systematically build the application, ensuring a reliable and efficient process.

- **Deploy Stage:**
  - Orchestrates the deployment process on AWS Elastic Beanstalk, seamlessly bringing the application to life on the cloud.

## Contributor

- [GreatClasher](https://github.com/GreatClasher)

Feel free to contribute and enhance this project!
