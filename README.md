# **Azure ML Iris Flower Classification**

## **Description:**

This project leverages Azure Machine Learning to build and deploy a machine learning model for classifying flower species based on the Iris dataset. 
It utilizes Python and the Azure ML SDK for training, deployment, and web app integration. This was part of hand-on-training of the AIDI-2004 program

## **Project Structure:**

* **.github/workflows**: Contains the configuration for Azure App Service build and deployment workflow.
* **classifier1.pkl**: Trained model pickle file will be used with Azure ML to predict flower types based on sepal and petal measurements.
* **app.py**: Python scripts for model deployment and web service creation.
* templates: Directory to store html file for web app.

## **Prerequisites:**

* Azure subscription (free tier available)
* Basic understanding of Python and machine learning concepts

## Project Steps

### Project Build
The project was constructed using Azure Machine Learning following these key steps:

1. Workspace Creation: An Azure Machine Learning workspace was established to manage the project's resources.
2. Dataset Import: The Iris dataset was imported into the workspace.
3. Data Preparation: The dataset was cleaned and preprocessed for model training.
4. Model Training: A machine learning model (classifier1.pkl) was trained using an appropriate algorithm (e.g., Support Vector Machine, Random Forest, Logistic Regression).
5. Model Evaluation: The trained model's performance was assessed using metrics like accuracy, precision, recall, and F1-score.

### Deployment
The trained model was deployed as a web service using Azure App Service. The deployment process involved:

1. Web App Creation: An Azure App Service web app was created to host the model.
Deployment Configuration: The deployment workflow was configured to automatically deploy the model to the web app upon code changes.
2. Model Endpoint: A REST API endpoint was exposed to allow users to submit flower measurements and receive predictions.

### Maintenance
1. Model Retraining: The model can be periodically retrained with new data to improve accuracy.
2. Performance Monitoring: The web service's performance should be monitored to identify any issues or bottlenecks.
3. Security Updates: The project dependencies and Azure platform components should be kept up-to-date with the latest security patches.


## **Getting Started:**

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/MOAZ47/Azure-ML-Iris-Flower-Classification.git
   ```
2. **Set Up Azure Credentials:**
   - Follow the Azure ML documentation to set up your Azure environment and obtain necessary credentials.

## **Usage:**

1. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
2. **Run the application (replace with appropriate command if different):**
   ```bash
   python app.py
   ```
