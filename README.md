

# AWS Deployment Practice - Predict Diabetes

This repository contains the code and necessary files to deploy a Flask web application to AWS using Elastic Beanstalk. The application is a simple model to predict the probability of a person having diabetes based on input parameters like age, BMI, blood pressure, etc.

## Files

- `application.py`: This is the main Flask application file.
- `model.pkl`: This is the serialized Random Forest Classifier model that has been trained on the diabetes dataset.
- `requirements.txt`: This file contains the list of packages required to run the application.
- `.ebextensions/`: This directory contains configuration files for Elastic Beanstalk.

## Usage

To run the application locally, you will need to have Python 3 installed. Clone this repository and run the following commands:

```bash
pip install -r requirements.txt
python application.py
```

Open a browser and go to `http://localhost:5000` to view the application.

To deploy the application to AWS Elastic Beanstalk, follow the steps mentioned in the official [AWS Elastic Beanstalk documentation](https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/GettingStarted.html).

## Results

The output results of the model are as follows:

---

![D1](https://user-images.githubusercontent.com/70787869/230753945-1b795cec-7ee0-429e-84d6-3629161a6de4.png)

---

![D2](https://user-images.githubusercontent.com/70787869/230753946-b8dba8c2-79a0-4bb4-930a-87411e3ca972.png)

---

![D3](https://user-images.githubusercontent.com/70787869/230753949-4dd1a10f-a0a4-447d-a52a-4136f18504ef.png)

---

### ENJOY DATA SCIENCE 'N' CODING 🐍😎
