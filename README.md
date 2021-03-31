# Income_vs_Pollution

An attempt to use linear regression and US income data to predict pollution levels at US county level.
While the modelling needs work, I have decided to include it in my portfolio as it provides a good 
example of cleaning and prepping data, especially for the income dataset.

The 'USIncome_vs_Pollution.ipynb' Jupyter Notebook file hasn't been rendering properly in git.
I believe this is related to a known issue. To overcome, I've provided an html vesion of the file 
('USIncome_vsPollution.html'), download it to view in your browser. Images of project output including 
visualizations are embedded.

If you'd like to run the project, first download all code and data, leave the data directory and 
sub-directories as they are, and unzip the pollution_us_2000_2016.zip in the data/USPollution directory.
From there, the file should run fine, provided the packages required (all package dependencies are 
imported at the top of the file) are installed.

This project has been parked in its current state, but I do have plans to find better pollution data for all counties 
and improve the methods used to aggregate the pollution data.

Package Dependencies:
* pandas
* numpy
* matplotlib.pyplot
* seaborn
* datetime
* statsmodels.formula.api
* sklearn.model_selection -> train_test_split 
* sklearn.linear_model -> LinearRegression
* sklearn -> metrics




