# The Ultimate Stage of Machine Learning
### Open standards for ML
#### Svetlana Levitan - IBM
## Some basics
* Data science = ML + business domain knowledge
* Can use structured or unstructured data
    * This talk will be using structured
    * Structured: tables with fields and variables
    * Unstructured: text stream
* Supervised vs unsupervised
    * Supervised: when you know the target
## The iris dataset
* Simple, sample dataset of some flowers
* From UCI ML depository
## (some) Models
* Clustering
* Linear regression
* Neural network
* Deep learning
* Decision tree
* Logistic regression
## Stages of ML
* Collect data
* Analyze & clean
* Transform data
* Build a model
* Deploy the model
* Monitor and update as needed
* Repeat
## Deployment challenges
* Different OS's and file systems
* Different languages
    * Different versions of languages
> There is a big disconnect between model building and model deployment
## Data Mining Group
* Attempts to fix these challenges
* IBM helped found
* Dmb.org/pmml
* Predictive Model Markup Language
## What is PMML
* A filetype to describe a built ML model
* Heirarchical, human-readable structure
* An open standard for deploying models to many types of environments and programs
### Main components of PMML
* Header
* Data directory
* Transformation dictionary
* Models
## PMML features
* Lots of PMML functions
* Some ML models
* Similar syntax to HTML
* Can be used for model visualization as well as scoring
## PMML use
* In python: [JPMML](https://github.com/jpmml)
* Can be used in R and use R's models
* [IBM SPSS](https://www.ibm.com/analytics/spss-statistics-software)
    * Supports many models exporting to PMML
* Watson studio
## How to score with PMML
* JPMML has options for that
* IBM SPSS can do it using the scoring wizard
## Other model deployment formats
### [PFA](http://dmg.org/pfa/)
* Newer
* Less support
* Lots of interest
### Pickle
* Python
### Mleap
* Open format, not a standard
### ONNX
* Not text based
## There are some containers for ML
* Ibm.biz/max-models