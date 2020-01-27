# Sentiment Analysis Web App and Deployment Using Pytorch & Amazon Sagemaker
Create a sentiment analysis web app using RRN and deploy using Amazon Sagemaker.  This project is part of the Udacity Deep Learning Nanodegree.

# Introduction

The notebook and Python files provided here, once completed, result in a deployed RNN performing sentiment analysis on movie reviews complete with publicly accessible API and a simple web page which interacts with the deployed endpoint. This project assumes some familiarity with Amazon SageMaker.  

Please see the [README](https://github.com/udacity/sagemaker-deployment/tree/master/README.md) in the root directory for instructions on setting up a SageMaker notebook and downloading the project files (as well as the other notebooks for using AWS Sagemaker).

# Instructions

1. Download the IMDB movie reviews data ([IMDb dataset](http://ai.stanford.edu/~amaas/data/sentiment/))
2. Prepare and preprocess the data (vocabulary)
3. Upload the processed data to Amazon S3
4. Build and train the pytorch model
5. Test the trained model (batch transform job)
6. Deploy the trained model for the web app using:
    * Amazon Lambda function
    * Amazon API Gateway

# Web App
![sentimentwebapp.png](sentimentwebapp.png)
