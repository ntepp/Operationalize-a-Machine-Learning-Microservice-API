[![CircleCI](https://circleci.com/gh/ntepp/Operationalize-a-Machine-Learning-Microservice-API.svg?style=svg)](https://circleci.com/gh/ntepp/Operationalize-a-Machine-Learning-Microservice-API)

## Operationalize a Machine Learning Microservice API

### Project Overview

In this project, we operationalize a Machine Learning Microservice API. 

In this project we deploy a Python flask application that serves out predictions (inference) about housing prices through API calls. We have as input a model that has been trained to predict housing prices in Boston according to several features, such as average rooms in a home and data about highway access, teacher-to-pupil ratios, and so on. The data is initially taken from Kaggle, on [the data source site](https://www.kaggle.com/c/boston-housing).

### Project goal

The project goal is to operationalize this working, machine learning microservice using [kubernetes](https://kubernetes.io/). In this project you will:
* Test the project code using linting
* Complete a Dockerfile to containerize this application
* Deploy the containerized application using Docker and make a prediction
* Improve the log statements in the source code for this application
* Configure Kubernetes and create a Kubernetes cluster
* Deploy a container using Kubernetes and make a prediction
* Upload a complete Github repo with CircleCI to indicate that your code has been tested


---

## Setup the Environment

* Create a virtualenv and activate it
* Run `make install` to install the necessary dependencies

### Running `app.py`

1. Standalone:  `python app.py`
2. Run in Docker:  `./run_docker.sh`
3. Run in Kubernetes:  `./run_kubernetes.sh`

### Kubernetes Steps

* Setup and Configure Docker locally
* Setup and Configure Kubernetes locally
* Create Flask app in Container
* Run via kubectl
