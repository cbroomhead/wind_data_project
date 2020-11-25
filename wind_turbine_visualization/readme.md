# Wind Turbines in the US - Data Exploration and Storytelling through Visualizations

## Included
The wind turbine dataset from USGS (2019) in a .csv format
Exploratory visualizations in both .ipynb and .html formats
Explanatory visualizations in both .ipynb and .html formats (html created with nbconvert to be view as slideshow)
2 image files
toggle-output.tpl file to run the explanatory notebook. 


## Run
Install: jupyter notebooks, nbconvert, pandas, numpy, matplotlib, seaborn, patsy, statsmodels
To run the notebooks, navigate to root directory of the project and type 'jupyter notebook'. 


## Project Introduction
This branch of the project is a market analysis  of turbines deployed in the state of California. It aims to evaluate different characteristics of turbines by manufactuerer with respect to rated capacity in kiloWatts. Since a wind turbine's primary prupose is to generate power, I was interested in exploring some of the independent variables provided in the dataset that could correlate to high performance in rated capacity for wind turbines.

Specifically, these variables are rotor diameter, rotor swept area, hub height, and a turbine's total height. 

Throughout the analysis, I answer the following questions and more:
- Who are the most common 5 turbine manufacturers deployed in CA?
- Out of those manufacturers, which one has ben deployed the longest?
- How do the top manufcaturers compare to each other with respect to rated capacity and other variables?
- Did certain design characteristcs allow certain manufacturers to outperform others?
- Are there certain models that were favored and do those have specific design characterists that affect rated capacity?

I make use of various types of plots such as histograms, scatter plots, regression plots, violin plots, and box plots to explore these relationships. There are single variate, bivariate, and multivariate plots used to illustrate findinds. 

## Summary of Findings

The analysis answered a few questions but ultimately lead to a provisional conclusion. It becomes apparent that there is no singular component in the dataset that is responsible for high performance in rated capacity. The data spans almost 40 years, so their are unsurprising trends such as increases in the size of turbines and subsequent components. In fact, the analysis does reveal high level of multicollenearity between the independent variables which somewhat muddle the findings on whether one feature or another significantly impact rated capacity.  

Further research into the subcomponents not provided in the dataset may reveal a different outcome. FOr instance, the analysis does provide evidence that even though two manufacturers have turbines that have similar design features and were deployed in similar times, they both fall into different ranges of rated capacity, revealing one manufacturer significantly outperforming the other. Why is that? Perhaps, components in the nacelle like drive train, generator, software, etc, could be interesting to look at when doing a market analysis based on wind turbine attribute. 

