# spacex-capstone-project
Final project for IBM Data Science Capstone - Falcon 9 Landing Prediction

##  SpaceX Falcon 9 Landing Prediction – IBM Data Science Capstone

This project is the final assignment in the IBM Data Science Professional Certificate. The goal is to predict the success of Falcon 9 first-stage landings using historical SpaceX launch data.

###  Objective

To build a classification model that predicts whether the Falcon 9 first stage will successfully land, enabling cost-efficient mission planning.

###  Key Components

* **Data Collection**:

  * Web scraping from Wikipedia (BeautifulSoup)
  * REST API calls to SpaceX API
  * Supplementary datasets in CSV/JSON format

* **Data Wrangling & Exploration**:

  * Data cleaning, feature engineering, normalization
  * SQL-based analysis and visualizations (matplotlib, seaborn)

* **Interactive Dashboard**:

  * Built with Plotly Dash to explore mission outcomes by payload, orbit, and site

* **Machine Learning Models**:

  * Logistic Regression, Decision Tree, KNN, SVM
  * Best Model: Support Vector Machine (sigmoid kernel)
  * Accuracy: **83.33%** | F1 Score: **\~0.83**

#  Files in This Repository

### PDF of Final Presentation
Full presentation of the SpaceX Falcon 9 launch prediction project

### labs-jupyter-spacex-Data wrangling.ipynb
This notebook covers the data cleaning and preprocessing steps for the SpaceX launch dataset. It handles missing data, feature engineering, and prepares the data for modeling.

### jupyter-labs-webscraping.ipynb
In this notebook, we use web scraping (BeautifulSoup) to collect SpaceX launch data from Wikipedia, which is then used for further analysis.

### jupyter-labs-spacex-data-collection-api.ipynb
This notebook focuses on using the SpaceX REST API to collect structured data about SpaceX launches. It queries various endpoints to retrieve mission details, payloads, rockets, and outcomes.

### lab_jupyter_launch_site_location (1).ipynb
This notebook investigates the relationship between launch site locations and mission outcomes, analyzing how different sites affect launch success rates.

### jupyter-labs-eda-sql-coursera_sqllite.ipynb
A notebook that applies SQL for exploratory data analysis (EDA) on SpaceX launch data stored in a SQLite database. It includes querying and visualizing the results using SQL techniques.

### edadataviz.ipynb
This notebook focuses on visualizing SpaceX data using EDA techniques. It uses libraries like Matplotlib and Seaborn for statistical visualization to understand patterns in the data.

### SpaceX_Machine Learning Prediction_Part_5.ipynb
The final notebook for building and evaluating machine learning models for predicting the success of Falcon 9 first stage landings. It covers multiple classification algorithms such as Logistic Regression, SVM, and Decision Trees.

