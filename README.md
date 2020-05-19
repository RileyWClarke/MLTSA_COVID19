# MLTSA_COVID19
MLTSA Spring 2020 Project - The handling of the Covid-19 outbreak in South Korea is unusual in how effective the country was in “flattening the curve” without imposing severe quarantine restrictions. We have done work trying to understand and characterize the outbreak in South Korea to gain insight into its success. Facebook Prophet’s modular regression model was chosen to analyze the death counts in Korea and look for changepoints. These changepoints were tentatively linked to policy decisions. Finally, we used this information to compare to several states in the United States. 

## Team Members:

Data Manager - Shaquann Seadrow

Methodology Manager - Jinbiao Ji

Communication Manager - Adam Marrs

Visualization Manager - Riley Clarke

Literature Manager - Adam Marrs


## Notebooks:
Covid19_data_set_acquisiton gathers all data sets and stores in appropriate directories from which some other notebooks run. 
(if you have access to the share drive you do not have to run this). If you want to run from scratch have to make share drive folder first. 

Covid19_data_prep takes look at data, creates new csv files as need. 

CovidModelsAdam is used to make Figures 1,3.

covid19_dist is used to compute distance metrics, produce Figure 6, Table 2.

COVID-19-South Korea.ipynb and Covid-19-US.ipynb are used to make Figure 5. 

Covid19_analysis.ipynb used to make figure 2, table 3, and discussion of cross correlations.

Covid19_weahter_prep was for if we get to the point where we will incorpoarate weather.

The NB'S written by shaquann will have to be downloaded then uploaded into the google drive (collab and git not synched). 



## Data:

Time.csv: South Korea data

us_covid19_daily.csv: US data

us_states_covid19_daily.csv: US data for each state
