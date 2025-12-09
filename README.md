# INST414 Final Project: Housing Prices 

<a target="_blank" href="https://cookiecutter-data-science.drivendata.org/">
    <img src="https://img.shields.io/badge/CCDS-Project%20template-328F97?logo=cookiecutter" />
</a>

Summary: INST414 project, based on the prices of housing, what features homes have, and what features/factors influence the prices of housing (location, number of bedrooms, area of property, etc). The project demonstrates visualizations of different factors in the home, specifically preferred area, and goes into machine learning for the property, predicting whether specific homes are priced higher due to the location that the home is in. 

Problem Statement: There's a perpetuating problem, where younger generation individuals are struggling with purchasing homes because they are priced in a way that may be unaffordable. As a result, this data and project seeks to delve into how homes are priced, and whether that could be perpetuated through the locations that individuals might be raised in—for example, gerrymandered locations that seek to put poorer areas together in order to purpetuate poverty. 

Project Goals and Objectives: I seek to develop a machine learning program that delves into what actually impacts housing prices, and whether younger generations can use that to their advantage. 

Dataset description: 
- Housing.csv:
    - Including 545 entries, derived from Kaggle
    - Has information such as price, area, bedrooms, bathrooms, stories, if it is near a main road, if there is a guest room, if there is a basement, if there is hot water heating, if there is air conditioning, if there is parking, if it is in a preferred area, and if the house was recently furnished.
      
Installation/setup instructions: There is a dataset in the Github under housing folder that is titled 'Housing.csv", that is where the dataset is. Sprint 2 includes the visualizations, Sprint 3 includes the machine learning. to access data, change the csv location to the dataset uploaded into the GitHub. 

Methods/tools/technologies used: 
- Python language, using pandas, numpy, matplotlib, seaborn, stats, sklearn
- Using linear regression
- Using Google Colab and Github 

Key results and conclusions: 
- While area does influence price (slight positive correlation), properties of the same size can vary significantly in price, likely due to unmodeled factors like locations, superior amenities, or varying conditions
- Rather than only one thing impacting price, there are several elements that impact the price of a home. 

Usage examples: 
- This project and dataset could be expanded to determine if there are any other stronger elements that impact housing price. Additionally, if paired with specific locations, this could predict prices of newly uploaded homes to determine what is a reasonable price given specific factors like location, area of property, number of bedrooms, bathrooms, etc. 

## Project Organization

```
├── LICENSE            <- Open-source license if one is chosen
├── Makefile           <- Makefile with convenience commands like `make data` or `make train`
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- A default mkdocs project; see www.mkdocs.org for details
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── pyproject.toml     <- Project configuration file with package metadata for 
│                         housing and configuration for tools like black
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
├── setup.cfg          <- Configuration file for flake8
│
└── housing   <- Source code for use in this project.
    │
    ├── __init__.py             <- Makes housing a Python module
    │
    ├── config.py               <- Store useful variables and configuration
    │
    ├── dataset.py              <- Scripts to download or generate data
    │
    ├── features.py             <- Code to create features for modeling
    │
    ├── modeling                
    │   ├── __init__.py 
    │   ├── predict.py          <- Code to run model inference with trained models          
    │   └── train.py            <- Code to train models
    │
    └── plots.py                <- Code to create visualizations
```

--------

