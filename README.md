# Practical Data Science on AWS Cloud Specialization

This repository contains my code solutions to the labs of the Practical Data Science on AWS Cloud Specialization offered by DeepLearning.AI on Coursera. This specialization teaches how to use various AWS services and tools to perform data analysis and machine learning tasks on the cloud.

## Table of Contents

- Analyze Datasets and Train ML Models using AutoML
- Build, Train, and Deploy ML Pipelines using BERT
- Optimize ML Models and Deploy Human-in-the-Loop Pipelines


## Analyze Datasets and Train ML Models using AutoML

This course covers how to use AWS Data Wrangler, AWS Glue, Amazon Athena, Amazon SageMaker Clarify, Amazon SageMaker Autopilot, and Amazon SageMaker BlazingText to perform data analysis and machine learning tasks on the cloud.

### Lab 1: Register and visualize dataset

In this lab, you will learn how to:

- List and access the Women's Clothing Reviews dataset files hosted in an S3 bucket.
- Install and import AWS Data Wrangler.
- Create an AWS Glue Catalog database and list all Glue Catalog databases.
- Register dataset files with the AWS Glue Catalog.
- Write SQL queries to answer specific questions on your dataset and run your queries with Amazon Athena.
- Produce and select different plots and visualizations that address your questions.

!A screenshot of a plot showing the distribution of ratings by age group

### Lab 2: Detect data bias with Amazon SageMaker Clarify

In this lab, you will learn how to:

- Download and save raw unbalanced dataset.
- Analyze bias with open source Clarify.
- Balance the dataset.
- Analyze bias at scale with a Amazon SageMaker processing job and Clarify.
- Analyze bias reports before and after balancing the dataset.

!A screenshot of a bias report showing the pre-training bias metrics

### Lab 3: Train a model with Amazon SageMaker Autopilot

In this lab, you will learn how to:

- Dataset review.
- Configure the Autopilot job.
- Launch Autopilot job.
- Track Autopilot job progress.
- Feature engineering.
- Model training and tuning.
- Review all output.
- Deploy and test best candidate model.

!A screenshot of the Autopilot job summary showing the best candidate model

### Lab 4: Train a text classifier using Amazon SageMaker BlazingText built-in algorithm

In this lab, you will learn how to:

- Prepare dataset.
- Train the model with Amazon SageMaker BlazingText.
- Deploy the model.
- Test the model.

!A screenshot of the model testing results showing the accuracy and confusion matrix

## Build, Train, and Deploy ML Pipelines using BERT

This course covers how to use Amazon SageMaker processing job, Amazon SageMaker Feature Store, Amazon SageMaker Debugger, Amazon SageMaker Profiler, Amazon SageMaker Pipelines, and Amazon SageMaker Model Registry to build, train, and deploy machine learning pipelines using BERT.

### Lab 1: Feature transformation with Amazon SageMaker processing job and Feature Store

In this lab, you will learn how to:

- Configure the SageMaker Feature Store.
- Transform the dataset.
- Inspect the transformed data.
- Query the Feature Store.

!A screenshot of the Feature Store showing the online and offline features

### Lab 2: Train a review classifier with BERT and Amazon SageMaker

In this lab, you will learn how to:

- Configure dataset.
- Configure model hyper-parameters.
- Setup evaluation metrics, debugger and profiler.
- Train model.
- Analyze debugger results.
- Deploy and test the model.

!A screenshot of the debugger showing the tensor distribution

### Lab 3: SageMaker pipelines to train a BERT-Based text classifier

In this lab, you will learn how to:

- Configure dataset and processing step.
- Configure training step.
- Configure model-evaluation step.
- Configure register model step.
- Create model for deployment step.
- Check accuracy condition step.
- Create and start pipeline.
- List pipeline artifacts.
- Approve and deploy model.

!A screenshot of the pipeline showing the steps and the status

## Optimize ML Models and Deploy Human-in-the-Loop Pipelines

This course covers how to use Amazon SageMaker Automatic Model Tuning, Amazon SageMaker Endpoints, Amazon SageMaker Augmented AI, and Amazon Comprehend to optimize machine learning models and deploy human-in-the-loop pipelines.

### Lab 1: Optimize models using Automatic Model Tuning

In this lab, you will learn how to:

- Configure dataset.
- Configure and run hyper-parameter tuning job.
- Evaluate the results.

!A screenshot of the tuning job showing the best training job

### Lab 2: A/B testing, traffic shifting and autoscaling

In this lab, you will learn how to:

- Configure and create REST Enpoint with multiple variants.
- Test the model.
- Show the metrics for each variant.
- Shift all traffic to one variant.
- Configure one variant to autoscale.

!A screenshot of the endpoint showing the traffic distribution and the autoscaling policy

### Lab 3: Data labeling and human-in-the-loop pipelines with Amazon Augmented AI (A2I)

In this lab, you will learn how to:

- Setup private workforce and Cognito pool.
- Create the Human Task UI using a Worker Task Template.
- Create a Flow Definition.
- Start and check the status of human loop.
- Verify the completion.
- View the labels and prepare data for training.
