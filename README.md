# Big Data Fraud Detection using PySpark  

## Project Overview
This project was done as part of a Big Data Analytics assignment. The main goal is to work with a large scale credit card financial transaction dataset using distributed computing to build an ML model to detect Credit Card Financial Fraud using PySpark in Python.

## Repository Structure

This repository contains 2 notebooks:

- Task1.ipynb → Spark initialisation, Loading the dataset, dataset schema and basic analysis
- Task2.ipynb → Data cleaning, No of Partitions and building a PySpark pipeline

## Dataset Details
The dataset is taken from Hugging Face contains financial transaction records. It includes details like:

- step:	Unit of time 
- type:	Transaction type
- amount:	Transaction value in simulated currency
- nameOrig:	Anonymized ID of sender
- oldbalanceOrg:	Sender’s balance before transaction
- newbalanceOrig:	Sender’s balance after transaction
- nameDest: Anonymized ID of recipient
- oldbalanceDest:	Recipient’s balance before transaction 
- newbalanceDest:	Recipient’s balance after transaction 
- isFraud	Binary flag: 1 if transaction is fraudulent
- isFlaggedFraud: 1 if transaction exceeds a flagged threshold

This dataset contains 21M rows and 11 columns.

### License
Apache 2.0 — freely usable with attribution

## Tools Used
- PySpark
- Python
- Jupyter Notebook
- GitHub
