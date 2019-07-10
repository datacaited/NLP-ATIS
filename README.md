# NLP-ATIS

## Libraries

* `pip install pyspark`
* `pip install pandas`
* `pip install numpy`

## Analysis with Descriptions

AtisAnalysis.ipynb

## Model Creation for Distribution

- model.py: Model creation with no analysis, creates AtisIntentModel.pmml
- Use nb_model.load("AtisIntentModel") to use model in other applications.

## Preprocessing Functions

- preprocessing.py

## Data Sets

- train.iob
- test.iob
- Note: Make sure these files are in the same folder the rest of the code is being executed from
