<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Final Project

**The demand level of travellers in data**

*Pedro Moreira*

*Data Analytics, Amsterdam 2020*

## Content
- [Project Description](#project-description)
- [Data Pipeline](#data-pipeline)
- [Organization](#organization)
- [Links](#links)

## Project Description
This project goal is to categorize travellers based on their country of origin. This categorization is based on reviews grabbed (via .CSV, API and web scrapping) from booking.com, expedia and yelp.

After a deep analysis of the data grabbed a model will be created to predict a match level of the traveller to the business.

## Data Pipeline <img src="https://github.com/pmoreira1/Final-Project/raw/master/pics/data%20pipeline.png" alt="Data Pipeline">


## Organization
```
FINAL-PROJECT
│   .gitignore
│   dataset_importer.py			- Load csv dataset to aws MySQL instance
│   get_match_level.py			- Get match level for a specific business
│   get_recommendations.py		- Get top 10 of each category
│   Model decision.ipynb		- Workbook used to decide best model
│   model_creation.py			- Script to create models for top 10 Nationalities
│   Presentation.twb			- Tableau Presentation Pt. 1
│   README.md				- This File
│   Recommendations.twb			- Tableau Presentation Pt. 2
│   yelp_business_grabber.py		- Grab business from yelp (API)
│   yelp_review_grabber.py		- Grab reviews + user nationality (API + Web Scrapping)
├───data				
│       countries_with_codes.csv 	- Dataset with countries and codes
│       hotel_clean.csv			- Cleaned hotels dataset
│       mysql_reviews.csv		- csv to import into AWS (created in case script failed)
├───functions
│       db_class.py			- Class for database operations
│       functions.py			- Holds all functions
├───models				- Folder with models generated by `model_creation.py`
├───results
│       recommendations.csv 		- recommendations for Tableu presentation Pt. 2

```
## Links

[Repository](https://github.com/pmoreira1/final-project)

[Slides](https://docs.google.com/presentation/d/1j0eeq0fz75578fAVJXVEYlf8t-NFS1X-Zo07Bfz8IWA/edit?usp=sharing)

