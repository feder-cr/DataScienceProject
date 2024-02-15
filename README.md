University project of the course "INTRODUZIONE ALLA DATA SCIENCE" of the computer science university of Genoa

Ecco una versione più dettagliata del readme che copre tutti gli aspetti del programma:

# Streaming Platform Data Analysis
## Key Features
### Objectives
- Perform comparative analysis between Netflix and Disney+ platforms 
- Apply full data science pipeline from data collection to insights
- Hands-on practice of data science concepts and techniques

### Datasets
- Disney and Netflix title datasets 
  - Metadata like title, type, date added, genre etc. 
  - Enrichment data like IMDB, TMDB scores
- 4 datasets integrated provide multifaceted view 

### Data Loading and Preparation
- Importing CSV datasets into dataframes
- Combining titles, enrichment and country datasets  
- Handling missing values and duplicate rows 
- Data transformations for analysis suitability
  - Extracting year/month from dates
  - Determining number of genres

### Exploratory Data Analysis
- Statistical summaries of key variables  
- Analysis across dimensions like certification, type etc.
- Comparative analysis across the platforms
- Hypothesis testing for distribution differences 

### Multidimensional Analysis
- Constructed OLAP cube with dimensions:
  - Month
  - Content type 
  - Production country
- Slicing, filtering and aggregation capabilities   

### Predictive Modeling
- Developed classification model using Logistic Regression
- Predict content type - movie or TV show
- Features: popularity, ratings, metadata  
- 85% accuracy on test data

### Interactive Visualizations
- Graphics for distributions, comparisons and trends
- Dashboards for slicing OLAP cube on multiple axes 

## Key Technologies
- Python
- Jupyter Notebook
- Pandas
- Numpy
- Scikit-Learn
- Matplotlib
- Seaborn

## What I Learned
Importing, cleaning and transforming medium-size datasets
Identifying optimal data formats and structures
Applying multivariate analysis techniques
Training and evaluating classification models
Using visualizations to extract insights
