# README #

## Intro ##

I'm doing this project to learn data processing, data validation, text classification, model training, model evaluation, model persistence, FastAPI


## Project structure ##


`/data` - This folder is used for storing the csv file for training the ML model.

`/notebooks` - This is where we write jupyter notebooks before writing production code. We do this so that we keep the production code clean. In the Jupyter Notebooks we write debug code and test the code.

`/src` - This is where the production code goes in.

`/tests` - We write unit tests and other tests in this folder.


## Project milestones ##

### Milestone 1: Explore Data ###

**Goal**: Understand the data and format

**Steps**: 

- Load the csv file
- Identify problems that may occur in the data
- Identify useful statistics for finances
- How to visualize trends

**Definition Of Done**: A Jupyter Notebook that loads data and shows 5 different visualizations that tell something about the finances


### Milestone 2: Categorization ###

**Goal**: Create a ML model that categorizes transactions

**Steps**:

- How to turn transaction description like uber ride to numbers that the ML model understands
- Find a good algorithm for text classification
- Set up a model validation system so we know if the model is good
- Figure out what to do if I don't have enough data for some category

**Definition Of Done**: A model that can categorize a new transaction with >80% correctness and returns a condifence score.

### Milestone 3: API ###

**Goal**: REST API that serves the created logic

**Steps**:

- Choose endpoints I need
- How to structure response
- Handle wrong file format upload
- How to keep data in memory in between requests

**Definition Of Done**: API with 5 endpoints that work, Swagger docs and proper error handling

### Milestone 4: Predictions ###

**Goal**: Predicting future transactions

**Steps**:

- Find the simplest way to predict
- How to handle upcoming holidays
- How to measure how good the predictions are
- Handle low data count

**Definition Of Done**: An endpoint that predicts the next month with a confidence interval

### Milestone 5: Production ###

**Goal**: Code that could go into production

**Steps**:

- How to persist data if the server goes down
- How to test code
- Initialize Docker
- How to handle multiple users

**Definition Of Done**: Dockerized app, 70% test coverage,



