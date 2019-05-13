# sagemaker-rec-demo

**Building a Recommender System with Amazon SageMaker Factorization Machines and BlazingText**


## Contents

Notebook: `fm_amazon_recommender.ipynb`

### Main Workshop:
- Background (Factorization Machines)
- Setup
	- Spin up SageMaker hosted notebook instance in console
	- Add SageMaker IAM policy to this SageMaker notebook to allow S3 read/write access
	- Create new S3 bucket (first cell)
	- Import necessary libraries (second cell)
- Dataset
	- Overview
	- Source: [Amazon Reviews Public Dataset](https://s3.amazonaws.com/amazon-reviews-pds/readme.html)
	- Features
- Data preprocessing
- Training
	- Create SageMaker estimator
	- Launch training job
- Host
	- Deploy endpoint to perform inference


### Extra Credit: 
- Background (New challenges, word2vec, BlazingText)
- Data Augmentation
- Dimensionality reduction with t-SNE
- Train
- Host