## END TO END PROJECT

import dagshub
dagshub.init(repo_owner='palakbansal8810', repo_name='DataScience-Project', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)


MLFLOW_TRACKING_URI=https://dagshub.com/palakbansal8810/DataScience-Project.mlflow
MLFLOW_TRACKING_USERNAME=palakbansal8810
MLFLOW_TRACKING_PASSWORD=7104284f1bb44ece21e0e2adb4e36a250ae3251f
python script.py