# covid-ifr

### Data and code for estimating age-specific COVID-19 infection fatality rates in developing countries using a Bayesian hierarchical model 

**IFR Data.xlsx**: contains data on seroprevalence studies, test characteristics, COVID-19 fatalities, and age distributions for 26 locations in developing countries: a subset of the locations provided in [Levin et al., 2022](http://dx.doi.org/10.1136/bmjgh-2022-008477).

**data_dictionary.xlsx**: describes the variable names used in IFR Data.xlsx

**ifr.R**: cleans the data and samples from the posterior distribution using RStan

**ifr.stan**: Stan code for sampling from the posterior distribution
