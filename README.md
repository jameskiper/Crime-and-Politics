## Violent Crimes in States 

This data project analyzes the violent crime rates over the past 10 years from each State to see which States have the highest and lowest violent crime rates during 2011 through 2020. We will also be looking at the overall violent crime rates and the population in the United State during the last 20 years to see if there has been a population growth and if there has been an increase or decrease in the violent crime rates over the past 20 years from 2000 to 2020 in the United States population.

## Introduction 

The project focuses on examining Violent Crimes rates per States and Population growth during the years 2011 through 2020.
- What are the top states with the highest and lowest crime rates over the past 10 years?
- Has there been any growth in the United States population during the last 20 years? 
- Has there been an increase or decrease in violence in the last 20 years?

## Data Files

The following data files are included in this repository:
- crimes.dataset.csv
- violent_crime_rates_all_years.csv
- 2020_population_violent_crime.csv

These datasets contain crime-related crime rates by state from 2011 to 2020. The United States population and Violent crime rates of the past 20 years that will be used for this analysis.

## Data Analysis

### Questions to Answer:
1. Has the trends in crime rates over the past 10 years increased or decreased? 
Yes, the crime rates have decreased in the last 10 years.

2. What is the population growth and violent crimes rates over the last 20 years from 2000 to 2020?
The population growth has grown 17.80% between 2000 and 2020 and the crime rates had decrease by 0.43% over the last 20 years between 2000 to 2020.

3. What states had the highest and lowest crime rates over the last 10 years from 2011 to 2020?
   The State with the hightest crime rates was Washington D.C. and the States with the lowest crime rate were Maine and Vermont.

## Outcome of the Data Analysis

The overall violent crime rates per year have dropped from 1,425,486 starting in the year 2000 to 1,313,105 to the year 2020 which 
results in an overall decrease of 0.043% in violent crime rates for the percentage of the population per year in the United States from 2000 to 2020. The overall population has grown from the year 2000 to 2020 by 17.80% over the last 20 years. The States with the highest crime rates was Washington D.C. from 2011 to 2020. The top states with the lowest violent crime rates were Vermont during 2013-2015 and Maine during 2011-2012 and 2016-2020.


### Running the Analysis

Follow these steps to run the data analysis project locally:

### Prerequisites
- Python 3.11.4
- Jupyter Notebook 6.5.4

### Setting Up a Virtual Enviroment
To run this project, its is recommended to use a virtual environment.
Follow these steps to set it up.

1. Create an empty directory and navigate to it.

2. Clone the repository by using
    git clone https://github.com/jameskiper/States-and-Violent-Crime-Rates-.git
    
    
3. Set up a virtual environment: 

    For Windows use command to create a virtual environment
     python -m venv venv
    
    To activate virtual environment use command
    .\venv\Scripts\activate 

    OR

    For macOS/Linux use command to create a virtual environment
    source venv/bin/activate 

    To activate virtual environment use command
    source venv/bin/activate
    

4. Install dependencies:

    Install the required packages and dependencies using
    pip install -r requirements.txt command.

5. When you are done working in the virtual environment,
   you can deactivate it by running the following command: deactivate

### Usage:
1. To run my script:
     Open my datafiles folder and open Edit_Finished_code_dataframe_for_project-1.ipynb to run my project script.

2.  Use jupyter notebook "main.ipynb"  
    

### Project Requirement Fulfilled:

1. Read two CSV files, Scrape one piece of data from the internet, merge two data sets and calculate new values.
2. Cleaned Data.
3. Used Matpotlib to make 3 visualizations to display my data.
4. Created a venv.
5. Annotate JPY and write clear README. 

### Data Sources 

https://www.kaggle.com/datasets/mathchi/violent-crime-rates-by-us-state/

https://en.wikipedia.org/wiki/List_of_U.S._states_and_territories_by_violent_crime_rate