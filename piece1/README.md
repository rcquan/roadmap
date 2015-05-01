# Piece 1

GRAPH Lead: Peter Muennig (pm124@columbia.edu)  
Team Members: Ryan Quan (rcq2102@columbia.edu), Jacquie Cheung (jc3987@columbia.edu)

## Deliverable Descriptions

* `costs`
    - `cost_estimates.xlsx` - main workbook containing relevant cost estimates per capita in constant 2013 and 2014 USD;
    - `References` - directory of literature used to pull cost estimates
* `dalys`
    - `roadmap_dalys_database.xlsx` - main workbook containing relevant DALY estimates at multiple levels of stratification; individual comma-delimited version available in the `tables` directory;
    - `docs` - report detailing methodology and results for DALY estimation (technical and brief versions);
    - `plots` - individual PDF and PNG graphs from the above report

## Methodology Overview

### DALYs Estimation

For a more thorough explanation of the methodology used to estimate DALYs for NYC, please refer to the [technical report](http://rpubs.com/rcquan/roadmap-dalys) in the `dalys` directory.

#### Data Collection

The DALY is a year of life lived in perfect health and consists of two elements: 1) YLL (years of life lost) and 2) YLD (years lost to disability). Data will be provided by the DOH and will be updated using the 2010 Global Burden of Disease (GBD) estimates.

For YLL, we will obtain the following data from NYCDOHMH:
* Disease prevalence
* Age-, gender-, and race-specific mortality rates for New York City (2013)
* Age-, gender-, and race-specific mean age of onset for each condition

For YLD, we will obtain 2010 disability weights from the GBD data, which also has the following elements:
* Duration stratified by sex and age groups (national and GBD study)
* RR mortality stratified by sex and age groups (national and GBD study)
* Remission rate (national and GBD study)
* Case fatality (national and GBD study)
* Disability weight used in the GBD 2010 study

#### Calculations

The NYCDOHMH previously estimated YLD based mainly on national rates where:

1. YLD = (YLD/YLL from national study) * (YLL from NYC mortality data)
2. YLD = (YLD/YLL from national study) * (NYC population)

We will repeat this with 2013 mortality data and 2010 rates. Where we can find them, we will also modify the prevalence data and other data elements for NYC.

### Cost Estimates

#### Data Collection

The following cost data will be collected from literature reviews to estimate economic losses due to mental illness in NYC:

* Lost productivity and leisure time
* Medical system costs
* Criminal justice system costs/social service costs

The Uniform Crime Reports has the total costs of incarceration. We need to figure out the percentage of these are linked to mental illness/substance abuse from the literature.

#### Standardization

To standardize these, we need to do the following:

* Extract lost productivity and leisure time losses due to selected condition with preference for NYC-specific estimates where found
* Adjust costs to constant 2013/2014 dollars using the consumer price index
* Divide by the reference population and report costs per capita

Special Note: Medical costs need to be separately extracted and adjusted to reflect NYC costs. We need to be careful to separate out studies that use charges from those that use costs. Those that use charges need to be adjusted to costs. Peter’s textbook has the relevant tables in the back.


