# social-interactions-ml

Columbia University in the City of New York

Sparsh Srivastava (ss6381), Rohan Arora (ra3091)

## Project Description

This repository provides the files and scripts necessary for the research study "Catalyzing Social Interactions in Mixed Reality". The study aims to understand the impact of mixed reality features on social interactions, through an empirical study with over 40 participants.

## Repository Structure

The repository is structured as follows:

- `data/`: Contains the raw data collected from the study.

- `docs/`: Contains notes and documentation that informed the research study.

- `final_models_and_metrics/`: Contains the final models and metrics produced during cross validation for finding the best models for the study.

- `milestones/`: Contains the milestone reports submitted throughout the semester.

- `models/`: Contains the best trained models found using cross validation.

- `scripts/`: Contains the scripts used for data preprocessing, feature extraction, and model training.

- `surveys/`: Contains the surveys used for data collection.

## Data Collection

The data was collected through a survey that was administered to participants. The survey was created using Google Forms and was distributed to participants through a study in Prolific. The survey collected information about the participants' demographics, focus group information, and their decisions on social interactions.

## Data Preprocessing

The data preprocessing script is used to clean the raw data collected from the survey. The script removes any unnecessary columns, renames columns, and formats the data for further analysis.

## Survey Generation

The survey generation script, located in '/scripts/scenario_builder.ipynb', is used to generate the survey that was administered to participants.

## Model Training

The model training script, located in '/scripts/model.ipynb' is used to train the models on the preprocessed data. The script uses cross validation to find the best model for the study.

## Analysis

The analysis script, located in '/scripts/data_distribution.ipynb', is used to analyze the distribution of the data collected from the survey. The script provides insights into the demographics of the participants and their decisions on social interactions. The '/scripts/prompt.ipynb' script is used to analyze the responses from a ChatGPT input to generate an analysis.

## Demo

The demo script, located in '/scripts/demo.ipynb', is used to demonstrate the use of the models trained on the data. The script provides a sample input and output for the models.
