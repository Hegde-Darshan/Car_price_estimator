# Documentation

This document serves as a reference for navigation for all the folders in the Mini-Hackathon project directory 


## Codes and notebooks
    1.  Data_cleansing
        Notebook that accounts for first stage of data cleaning and manipulation
    
    2.  EDA
        Exploratory Data analysis. This notebooks gives a birds-eye view on the data
    
    3. Feature_engg and model_selection
        This notebook refers to all the data manipulations and transformations done, extracting and selecting features. Then, model selection by training crude machine learning algorithms and analysing their performance metrics

    4.  Model_tuning
        After selecting models, the selected models are hyperparameter-tuned to see which has the best fits for the given data. The final model is trained based on these results.
    
    5. final_model
        The selected model and the best performing set of hyperparameters are trained almost on the entire dataset to get a final predictive model.

    6. Test
        Contains some test codes and observations. (not relevant to the final model)


## data
    This has all the csv and excel files used/produced during any stage of model development


## metrics and visuals
    This folder is a dump for pushing all the visualizations during EDA and model selection. It also has outputs of model performance during model selection.


## parameter search results
    Dump for results of hyperparameter tuning


## Saved models
    Contains the pickle dump of the final trained model


- Interactive.ipynb 
This is a notebook to experiment with the final trained model, which has interactive widgets embedded



