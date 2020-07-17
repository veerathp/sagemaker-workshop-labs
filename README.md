# Sagemaker Workshop Labs

### Prerequisites
Setup Amazon SageMaker Studio and clone GitHub repository 

- Step 1: Login into the AWS console, navigate to Amazon SageMaker service 

- Step 2: Create Amazon SageMaker Studio Session in Oregon (us-west-2) region. Open it. 

- Step 3: Clone GitHub repository within the Amazon SageMaker Studio. GitHub repo: https://github.com/veerathp/sagemaker-workshop-labs
   
   To clone, go to the File→Terminal and then copy the command below
   ```
  git clone https://github.com/veerathp/sagemaker-workshop-labs.git
   ```
### Labs

All labs should run using Data Science kernel 

#### Lab 1: Build, Train and Deploy ML models
Build, Train and Deploy Machine Learning models using Amazon SageMaker / DeerAR

- Open and run the Notebook Instances in Amazon SageMaker Studio located in /01-01-DeepAR/deepar_chicago_traffic_violations.ipynb

#### Lab 2: Hyper Parameter Optimization
Hyper Parameter Optimization using Amazon SageMaker 
- Open and run the Notebook Instances in Amazon SageMaker Studio located in /02-sagemaker-hpo-xgboost/hpo_xgboost_direct_marketing_sagemaker_python_sdk.ipynb

Note: The first lab will take about 20-30mins to run, once completed move to the notebook below to analyzing the training jobs. Enter the name of the training job in the tuning_job_name = 'ENTER TRAINING JOB'

- Open and run the Notebook Instances in Amazon SageMaker Studio located in /02-sagemaker-hpo-xgboost/HPO_Analyze_TuningJob_Results.ipynb


#### Lab 3: Multi Model endpoints

Deploying Machine Learning models using Multi Model endpoints

- Open and run the Notebook Instance in Amazon SageMaker Studio located in /04-sagemaker-mme/xgboost_multi_model_endpoint_home_value.ipynb


#### Lab 4: Model monitoring 
Monitoring Machine Learning endpoints 
- Open and run the Notebook Instance in Amazon SageMaker Studio located in /03-sagemaker-model-monitor/SageMaker-ModelMonitoring.ipynb
