# **Azure ML Iris Flower Classification**

**Description:**

This project leverages Azure Machine Learning to build and deploy a machine learning model for classifying flower species based on the Iris dataset. 
It utilizes Python and the Azure ML SDK for training, deployment, and web app integration. This was part of hand-on-training of the AIDI-2004 program

**Key Features:**

* Machine Learning Model: Trains a model (classifier1.pkl) using Azure ML to predict flower types based on sepal and petal measurements (features in the Iris dataset).
* Deployment: Deploys the trained model as a web service on Azure.
* Web App Integration: Integrates the deployed model into a web application.

**Prerequisites:**

* Azure subscription (free tier available)
* Basic understanding of Python and machine learning concepts

## Project Steps

1. Data Preparation:

   - Import and explore the Iris dataset.
   - Preprocess data as necessary (e.g., handling missing values, feature scaling).
   - Split the dataset into training and testing sets.

2. Model Training:

   - Select an appropriate machine learning algorithm (e.g., Logistic Regression, Support Vector Machine, Random Forest).
   - Train the model using the training dataset.
   - Evaluate the model's performance using metrics like accuracy, precision, recall, and F1-score.

3. Model Deployment:

   - Deploy the trained model as a web service using Azure Machine Learning.
   - Create a web app to interact with the deployed model.

**Getting Started:**

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/MOAZ47/Azure-ML-Iris-Flower-Classification.git
   ```
2. **Set Up Azure Credentials:**
   - Follow the Azure ML documentation to set up your Azure environment and obtain necessary credentials.

**Usage:**

1. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
2. **Run the application (replace with appropriate command if different):**
   ```bash
   python app.py
   ```
