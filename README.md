# End_to_End_ML_Project_with_mlflow_and_Deployment

# How to run?
### STEPS:

Clone the repository

```bash
https://github.com/rrizwan98/End_to_End_ML_Project_with_mlflow_and_Deployment.git
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n mlproj python=3.8 -y
```

```bash
conda activate mlproj
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```


```bash
# Finally run the following command
python app.py
```

Now,
```bash
open up you local host and port
```



## MLflow

[Documentation](https://mlflow.org/docs/latest/index.html)


##### cmd
- mlflow ui

### dagshub
[dagshub](https://dagshub.com/)

MLFLOW_TRACKING_URI=https://dagshub.com/rrizwan98/End_to_End_ML_Project_with_mlflow_and_Deployment.mlflow \
MLFLOW_TRACKING_USERNAME=rrizwan98 \
MLFLOW_TRACKING_PASSWORD=d685b0bd147ef96de518be68b7d128d4d70ca84f \
python script.py

Run this to export as env variables:

```bash

export MLFLOW_TRACKING_URI=https://dagshub.com/rrizwan98/End_to_End_ML_Project_with_mlflow_and_Deployment.mlflow

export MLFLOW_TRACKING_USERNAME=rrizwan98 

export MLFLOW_TRACKING_PASSWORD=d685b0bd147ef96de518be68b7d128d4d70ca84f

```
