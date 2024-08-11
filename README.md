# Build a ML Workflow for Scones Unlimited on Amazon Sagemaker

## Project Overview

This project is part of Udacity Nanodegree program [AWS Machine Learning Fundamentals](https://www.udacity.com/enrollment/nd189-aws-fundamentals). This project demonstrates how to deploy and monitor a machine learning workflow specifically designed for image classification. The notebook uses the CIFAR dataset, a well-known image classification dataset, to simulate real-world challenges encountered by Scones Unlimited in their image classification tasks. The workflow involves setting up the environment, staging data, developing and training the model, and finally, deploying and monitoring the model in a production environment.

## Prerequisites

You should have created **Sagemaker Studio User**. To launch the studio:

* Proceed to open up the AWS console from the AWS Gateway.
* Click through the AWS console to Amazon Sagemaker.
* Click through the main Sagemaker page to Amazon Sagemaker Studio from the left hand toolbar.
* If a user does not exist already in the Sagemaker Studio Control Panel, Add user.
* Select an execution role that has full Sagemaker Access, otherwise you can create a new role.
* Create a role and proceed with creating the user.

## Project Steps

### Data Staging
The first step in the workflow is data staging, where the CIFAR dataset is prepared for use. This section covers:

1. **Data Extraction:** Downloading the CIFAR-100 dataset from the University of Toronto's hosting service.
2. **Data Transformation:** Converting the data into a usable format, suitable for model training.
3. **Data Loading:** Loading the transformed data into a production system.
This process is akin to an ETL (Extract, Transform, Load) pipeline that prepares the data for further processing.

### Model Development
In this section, you will build and train a machine learning model using the staged data. The key steps include:

1. **Model Architecture:** Define the architecture of the neural network model to be used for image classification.
2. **Training the Model:** Train the model using the CIFAR dataset, and fine-tune it to achieve optimal performance.
3. **Evaluation:** Evaluate the model's performance using standard metrics such as accuracy and loss, ensuring it meets the required benchmarks.

### Deployment and Monitoring
Once the model is trained and evaluated, the next steps involve deploying it into a production environment and setting up monitoring to track its performance:

1. **Deployment:** The trained model is deployed using SageMaker, making it accessible for real-time inference.
2. **Monitoring:** Set up monitoring tools to track the model's performance, detect any issues, and ensure it continues to perform as expected in a live environment.

## Usage 

To run the notebook:

* **Set Up the Environment:** Ensure you have the necessary kernel and instance as mentioned in the prerequisites.
* **Follow the Sections:** Execute the cells in each section sequentially, from data staging to deployment.
* **Monitor Outputs:** Observe the outputs and logs to understand how the model is performing at each stage.
* **Modify as Needed:** Feel free to tweak the parameters, model architecture, or deployment settings to suit your specific needs.

## Contributing

Contributions to this project are welcome! If you have suggestions for improving the workflow, model performance, or deployment strategies, feel free to open a pull request or submit an issue.

* **Fork the repository**
* **Create a new branch** for your feature or bug fix
* **Submit a pull request** with a detailed explanation of your changes
