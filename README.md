# Machine Learning Workshop

## Prerequisites

Sign in to the AWS console
   
   - Step 1. Paste the hash login URL associated to your name in a browser
   
   - Step 2. Click “AWS Console”, then “Open AWS Console”

Open Amazon SageMaker Studio 
   - Step 3. Navigate to Amazon SageMaker service
   
   - Step 4. Create Amazon SageMaker Studio session in Oregon (us-west-2) region. 
      
      Select "Quick start" with "Create a new role" in the "Execution Role" section, then click "Submit". This will take about 2-3 mins. 
      
      Once its completed and the Amazon SageMaker Studio domain has status "Ready", select "Open Studio".

Clone GitHub repository within the Amazon SageMaker Studio
   - Step 5. Within Amazon SageMaker Studio, go to the `File → New → Terminal` and then run following command 
   ```
  git clone https://github.com/veerathp/sagemaker-workshop-labs.git
   ```

## Hands-on labs

Use **Python 3 (Data Science)** kernel to run all labs below into SageMaker Studio. For SageMaker notebook instances use conda_python3.

### Lab 1: Build, Train and Deploy ML models
Build, Train and Deploy Machine Learning models using Amazon SageMaker / DeerAR

- Open and run the Notebook Instances in Amazon SageMaker Studio located in `/01-DeepAR/deepar_chicago_traffic_violations.ipynb`


### Lab 2: Hyper Parameter Optimization
Hyper Parameter Optimization using Amazon SageMaker. The first lab will take about 20-30mins to run, once completed move to the second notebook to analyzing the training jobs.

- Open and run the Notebook Instances in Amazon SageMaker Studio located in `/04-sagemaker-hpo-xgboost/hpo_xgboost_direct_marketing_sagemaker_python_sdk.ipynb`

- Cont. Open and run the Notebook Instances in Amazon SageMaker Studio located in `/04-sagemaker-hpo-xgboost/HPO_Analyze_TuningJob_Results.ipynb`. Make sure you replace the name of the training job



### Lab 3: Running experiments 
Running experiments and manage multiple trials
- Open and run the Notebook Instance in Amazon SageMaker Studio located in `/02-customer-churn/xgboost_customer_churn_studio.ipynb`


### Lab 4: Unsupervised ML algorithms
Build, Train and Deploy Machine Learning models for anomaly detection
- Open and run the Notebook Instance in Amazon SageMaker Studio located in `/03-unsupervised-random-cut-forest/random_cut_forest.ipynb`


### Lab 5: Multi Model endpoints

Deploying Machine Learning models using Multi Model endpoints

- Open and run the Notebook Instance in Amazon SageMaker Studio located in `/06-sagemaker-mme/xgboost_multi_model_endpoint_home_value.ipynb`


#### Additional Resources
- [Amazon SageMaker](https://aws.amazon.com/sagemaker/)
- [Amazon SageMaker Examples](https://github.com/awslabs/amazon-sagemaker-examples)
- [Amazon SageMaker Studio](https://aws.amazon.com/blogs/aws/amazon-sagemaker-studio-the-first-fully-integrated-development-environment-for-machine-learning/)
- [Amazon SageMaker Autopilot](https://aws.amazon.com/sagemaker/autopilot/)
- [Host Multiple Models with Multi-Model Endpoints](https://docs.aws.amazon.com/sagemaker/latest/dg/multi-model-endpoints.html)



