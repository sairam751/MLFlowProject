# MLFlowProject

https://dagshub.com/sairam751/MLFlowProject.mlflow

import dagshub
dagshub.init(repo_owner='sairam751', repo_name='MLFlowProject', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)