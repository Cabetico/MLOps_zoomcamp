# MODEL MATURITY

[Maturity Model Microsoft](https://learn.microsoft.com/en-us/azure/architecture/example-scenario/mlops/mlops-maturity-model)


### 0) NO MLOPS

* No automation
* All code in Jupyter
* Good level for POC projects

### 1) DEVOPS, NO MLOPS

* Some level of automation(developers helping DS team)
* Posible to deploy a model(web service)
* unit test, integration test, CI/CD
* Ops Metrics
--------
* No experiment tracking
* No reproducibility
* DS separated from engineers
* Take POC &rarr; Production

### 2) AUTOMATED TRAINING

* Training pipeline
* Experiment tracking
* Model Registry
* Low friction deployment
* DS Work with engineers
* This framework is ideally for multiple models in production

### 3) AUTOMATED DEPLOYMENT
* Easy to deploy(Human supervised deployment is not needed)
*  |Data Prep| &rarr; |Train Model| &rarr; |Deploy Model|

* A/B TEST | two models challeging each other

### 4) FULL MLOPS AUTOMATION

* Automatic Training
* Automatic Re-training
* Automatic Deployment





