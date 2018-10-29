# The Ultimate Stage of Machine Learning
### Open standards for ML
#### Svetlana Levitan - IBM
## Some basics
* Data science = ML + business domain knowledge
* Can use structured or unstructured data
    * This talk will be using structured
    * structured: tables with fields and variables
    * unstructured: text stream
* Supervised vs unsupervised
    * supervised: when you know the target
## The iris dataset
* simple, sample dataset of some flowers
* from UCI ML depository
## (some) Models
* clustering
* linear regression
* neural network
* deep learning
* decision tree
* logistic regression
## Stages of ML
* Collect data
* analyze & clean
* transform data
* build a model
* deploy the model
* monitor and update as needed
* repeat
## Deployment challenges
* different OS's and file systems
* different languages
    * different versions of languages
> There is a big disconnect between model building and model deployment
## Data Mining Group
* attempts to fix these challenges
* IBM helped found
* dmb.org/pmml
* Predictive Model Markup Language
## What is PMML
* A filetype to describe a built ML model
* Heirarchical, human-readable structure
* An open standard for deploying models to many types of environments and programs
### Main components of PMML
* header
* data directory
* transformation dictionary
* models
## PMML features
* Lots of PMML functions
* Some ML models
* similar syntax to HTML
* can be used for model visualization as well as scoring
## PMML use
* in python: [JPMML](https://github.com/jpmml)
* can be used in R and use R's models
* [IBM SPSS](https://www.ibm.com/analytics/spss-statistics-software)
    * supports many models exporting to PMML
* Watson studio
## How to score with PMML
* JPMML has options for that
* IBM SPSS can do it using the scoring wizard
## Other model deployment formats
### [PFA](dmg.org/pfa)
* newer
* less support
* lots of interest
### Pickle
* python
### Mleap
* open format, not a standard
### ONNX
* not text based
## There are some containers for ML
* ibm.biz/max-models