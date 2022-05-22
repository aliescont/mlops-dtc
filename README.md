
# MLOps Zoomcamp

<p align="center">
  <a href="https://datatalks.club" target="_blank">
    <img src="images/banner.png">
  </a>
</p>


This is a course offered by DataTalks Club. In this repo there is their original documentation along with my 

- Sign up here: https://airtable.com/shrCb8y6eTbPKwSTL (it's not automated, you will not receive an email immediately after filling in the form)
- Register in [DataTalks.Club's Slack](https://datatalks.club/slack.html)
- Join the [`#course-mlops-zoomcamp`](https://app.slack.com/client/T01ATQK62F8/C02R98X7DS9) channel
- [Tweet about the course!](https://ctt.ac/fH67W)
- Subscribe to the [public Google calendar](https://calendar.google.com/calendar/?cid=M3Jzbmg0ZDA2aHVsY2M1ZjcyNDJtODNyMTRAZ3JvdXAuY2FsZW5kYXIuZ29vZ2xlLmNvbQ) (subscription works from desktop only)
- [Youtube Playlist with all the videos](https://www.youtube.com/playlist?list=PL3MmuxUbc_hIUISrluw_A7wDSmfOhErJK)
- [Technical FAQ](https://docs.google.com/document/d/12TlBfhIiKtyBv8RnsoJR6F72bkPDGEvPOItJIxaEzE0/edit) 


## Overview

### Objective

Teach practical aspects of productionizing ML services — from collecting requirements to model deployment and monitoring.

## Syllabus

This is a draft and will change. 


### [Module 1: Introduction](01-intro)

* What is MLOps
* MLOps maturity model
* Running example: NY Taxi trips dataset
* Why do we need MLOps
* Course overview
* Environment preparation
* Homework

[More details](01-intro)

### Module 2: Experiment tracking

* Experiment tracking intro
* Getting started with MLflow
* Experiment tracking with MLflow
* Saving and loading models with MLflow
* Model registry
* MLflow in practice
* Homework


### Module 3: Orchestration and ML Pipelines

* ML Pipelines: introduction
* Prefect
* Turning a notebook into a pipeline
* Kubeflow Pipelines
* Homework 


### Module 4: Model Deployment 

* Batch vs online
* For online: web services vs streaming
* Serving models in Batch mode
* Web services
* Streaming (Kinesis/SQS + AWS Lambda)
* Homework


### Module 5: Model Monitoring

* ML monitoring vs software monitoring 
* Data quality monitoring
* Data drift / concept drift 
* Batch vs real-time monitoring 
* Tools: Evidently, Prometheus and Grafana
* Homework 


### Module 6: Best Practices

* Devops
* Virtual environments and Docker
* Python: logging, linting
* Testing: unit, integration, regression 
* CI/CD (github actions)
* Infrastructure as code (terraform, cloudformation)
* Cookiecutter
* Makefiles
* Homework


### Module 7: Processes

* CRISP-DM, CRISP-ML
* ML Canvas
* Data Landscape canvas
* [MLOps Stack Canvas](https://miro.com/miroverse/mlops-stack-canvas/)
* Documentation practices in ML projects (Model Cards Toolkit)


### Project

* End-to-end project with all the things above


## Running example

To make it easier to connect different modules together, we’d like to use the same running example throughout the course.

Possible candidates: 

* [https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page](https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page) - predict the ride duration or if the driver is going to be tipped or not


## Instructors

- Larysa Visengeriyeva
- Cristian Martinez
- Kevin Kho
- Theofilos Papapanagiotou 
- Alexey Grigorev
- Emeli Dral
- Sejal Vaidya


## Other courses from DataTalks.Club:

- [Machine Learning Zoomcamp - free 4-month course about ML Engineering](https://github.com/alexeygrigorev/mlbookcamp-code/tree/master/course-zoomcamp)
- [Data Engineering Zoomcamp - free 9-week course about Data Engineering](https://github.com/DataTalksClub/data-engineering-zoomcamp/)


## Partners

Thanks to our friends for spreading the word about the course

<p align="center">
  <a href="https://dphi.tech/">
    <img height="75" src="https://datatalks.club/images/partners/dphi.png">
  </a>
  <a href="https://www.confetti.ai/">
    <img height="75" src="https://datatalks.club/images/partners/confetti.png">
  </a>
</p>
