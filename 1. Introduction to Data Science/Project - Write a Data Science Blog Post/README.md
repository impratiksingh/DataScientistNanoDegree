# DataScientistNanoDegree
This repository will contains submissions and related contents from my  Udacity Data Scientist NanoDegree

## Table of Content
1. Installation
2. Project Motivation
3. File Description
4. Results
5. Licensing , Authors and Acknowledgements

## Installation

The associated Jupyter Notebook can be executed with Anaconda installation. Python 3+ would be suitable. geopandas will be required plotting geographical maps.

## Project Motivation 

I was interested in knowing what kind of Members of Parliament did we choose in the General Election of India 2019.
Questions of interest were :

1. What percent of MPs have criminal cases registered against them ?
2. Which states contributed most in polluting the parliament ?
3. What is the distribution of MPs on ground of Education Qualifications ? 
4. Is there a correlation between education qualification and criminal cases of MPS ?

## Project Overview
### a. Business Understanding
The outcomes of this project can be used by companies dealing with profiling the existing ministers on grounds of their background and 
develop a correlation between their performance after they are elected.Once these reports are circulated among the people , it will help them in making an informed decision in upcoming elections.

### b. Data Understanding
<ul> Data for the winners was collected from Election Commition Website </ul>
<ul> Data was examined for data quality checks </ul>
<ul> Data Exploration results are captured in the Notebook </ul>

### c. Prepare Data
<ul> Data Cleaning was done for reporting , consistent casing and removal of special characters etc. was performed. </ul>
<ul> Winners Data was wrangled to align it with the geojson data for plotting purposes  </ul>

### d. Data Modeling
<ul> This project did not have predictive data modelling , it was a data wrangling and visualisation project  </ul>

### e. Evaluate the Results
<ul> The resiults of this project are presented in for of visualisation / correlation and tables  </ul>
<ul> Possible next set of actions in this project could be to enable the analysis to drill down to local election results as well  </ul>

## File Descriptions
Winners.csv : List of all the winners with the information they submitted during filing their nomination . Details around education , criminality , asset , etc are captured here.
india_pc_2019_simplified.geojson : A constituency level geojson file for india.

## Results

The findings and related visualisations can be found at the blog post here.

## Licensing , Authors and Acknowledgements

Both data and code is freely avaialable to use.

Winners data was pulled from : https://www.myneta.info/
Geojson file was pulled from : https://github.com/datameet/maps/tree/master/parliamentary-constituencies



