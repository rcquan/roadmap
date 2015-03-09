# Mental Health and Substance Use in New York City: Burden, Cost, and Return on Investment

## Proposal

### Piece 1. Estimating DALYs and costs due to mental illness and substance use in New York City

The primary goal of our analysis is to understand the burden and costs associated with mental illness in New York City (NYC). The disability-adjusted life year is an estimate of healthy life lost to disability, and is conceptually equivalent to one year of life lived in perfect health. The DALY creates an estimate of morbidity that is equal to mortality by “weighting” the time one spends with a disability such that a year of life with a disability is some fraction of a year of life lived in perfect health. The basic formula for estimating DALYs lost to mental illness involves summing the years of life lost to disability (YLD) and the years of life lost (YLL). Thus, if a person with schizophrenia has a DALY score of 0.36, then every year of life she lives with schizophrenia is equal to 0.36 of a year of life lived in perfect health. To estimate DALYs, we therefore need the following information:

* Mean age of onset (this is similar across developed nations and can be obtained from the literature)
* Disease prevalence (via NYC HANES), coupled with demographically-weighted smoothed estimates
* The DALY score (this can be obtained from the 2010 Global Burden of Disease study)
* Mortality hazards or other estimates of years of life lost (from the literature)
 
The DOHMH has specifically asked for a ranking of mental illness among other conditions. To fulfill this request, we will need to analyze a set of other common conditions, as well. These will include other high burden diseases, including heart disease, cancer, accidents, stroke, and COPD. This analysis will involve replicating the analyses from the 2011 Global Burden of Disease report for established market economies, but substituting the prevalence data for New York City. We will incorporate smoothing approaches to align with the goal of small-area DALY estimates in the setting of limited prevalence data.
 
To estimate the economic burden of psychopathology, we will calculate the costs associated with:

* Lost productivity time, lost leisure time. These two costs are valued together at the median wage and are summed over 24 hours/365 days/year.
* Medical costs. These can either be calculated from scratch using billing/payer data (NYC SPARC data) or can be estimated on a per capita basis from the literature and then adjusted to 2014 New York City costs using a medical inflation index and relative cost data.
* Social services costs. Mental illness places a huge burden on the city’s social service infrastructure, including housing services.
* Policing/incarceration costs. These can be captured via the literature and via criminal justice databases. The cost is calculated by multiplying the attributable fraction of all criminal justice system contacts due to mental illness by the total criminal justice system costs to New York City.
* Caregiving costs. We will here leverage the literature regarding the economic costs due to caregiving and lost productivity of caregivers to estimate the potential costs of caregiving for mental illness in the City. 

### Piece 2. Mapping the burden,‘preventable burden’, ‘treatable burden’ and disparities in psychopathology and substance use in NYC

GRAPH unites a team with expertise in health policy, biostatistics, and epidemiology. We have previously conducted a systematic review of the prevention science literature against leading causes of death, including suicide, alcohol, and drug abuse. Capitalizing on this diverse expertise and experience, we aim to extend the above analyses to ‘tell the story’ of mental health and substance use in NYC.
 
In addition to calculating the burden and costs of psychopathology in New York City in piece 1, we aim to pursue a series of analyses to advance our understanding of meaningful treatment and prevention policy to address this burden and deliver the potential return on these investments to public and private payers. In that respect, we aim to perform several targeted analyses toward the following aims:
 
To extend our systematic review of rigorous, efficacious primary prevention interventions against leading causes of death to leading causes of psychopathology, including mood and anxiety disorders and psychosis, and substance use, including alcohol and drugs;

* To calculate the ‘preventable burden’ of psychopathology if rigorous, efficacious primary prevention interventions were applied across New York City, as well as the ‘treatable burden’ of psychopathology if funding for evidence-based treatment were extended throughout the City;
* To map both the burden, preventable burden, treatable burden, and disparities of psychopathology and substance use in New York City. While mapping granularity is limited by the quality of extant data, we hope to map to the zipcode level combining fine-area estimates and demographic smoothing where appropriate.
 
### Piece 3. Psychopathology and the costs of medical care in NYC

The NYC DOMH is interested in understand the contribution of psychopathology to medical care costs for care across high burden diseases in NYC among patients enrolled in public healthcare plans (Medicare and Medicaid). Therefore, in addition to directly pursuing the analyses outlined in pieces 1 and 2 above, we will also work directly with the DOMH team to advise on medical care cost analyses, on which our investigative team has expertise and experience.
 
### Timeline

The NYC DOMH would like to publish this report in the second quarter or 2015. In that respect, we aim to pursue a staged analysis. We aim to begin in February 2015. In that respect, we will complete analyses toward Pieces 1 and 2 by April 15th, working with colleagues at DOHMH throughout toward Piece 3 throughout our timeline.

# Analytic Plan

The objective of this analysis is to estimate DALYs lost and economic losses due to the following major categories of conditions (with about 100 conditions in total within these categories):

1. Major depression
2. Alcohol
3. Marijuana use
4. Heroin use
5. Cocaine use
6. Stimulant/hallucinogen use
7. Sedative tranquilizer use

For this analysis, we will need 7 major pieces of data for each of these major categories. It will not be possible to estimate economic losses for all 100 conditions because there will not be adequate data. The data we will require are as follows:

1. Disease prevalence
2. Age-, gender-, and race-specific mortality rates for New York City.
3. Age-, gender-, and race-specific mean age of onset for each condition listed above.
4. Lost productivity and leisure time
5. Medical system costs
6. Criminal justice system costs/social service costs
7. Prevention effectiveness

These data will be used to estimate the following elements.

1. **Interactive disease prevalence data maps**. This will be supplied by the NYCDOHMH for the smallest geographic units of analysis possible. For each unit, we will need roughly 100 cases in the numerator as a minimum. We can use blurring or other techniques to obtain estimates. These estimates should be available from their 2011 analysis. We will require these data for 5 age groups (0-4, 5-14, 15-24, 25-44, 45-64, 65-75, 75+). The challenge is that the NYCHANES and NSDH data are very out of date and the n is too low in both surveys. To increase their utility, we should use childhood (0-14), late adolescence/early adulthood (15-24), adulthood (25-64), and later life (65+). We will need to do a literature and data review to see what kinds of other surveys might be out there for NYC. 

2. **DALYs**. The DALY is a year of life lived in perfect health and consists of two elements: 1) YLL (years of life lost) and 2) YLD (years lost to disability).  We can estimate DALYs using NYC mortality counts stratified by age, sex, and race to compute YLL using 2013 mortality data and mean age of onset from the previous NYCDOHMH study. For YLLs, we will need 2010 disability weights and the mean age of onset. The following elements may be obtained from the GBD data:

* Duration stratified by sex and age groups (national and GBD study)
* RR mortality stratified by sex and age groups (national and GBD study)
* Remission rate (national and GBD study). We should do a literature review here to see if there are any data from NYC. Rufina Lee has data on intervention impacts on remission rates for NYC. This can be used to estimate the CEA of prevention effectiveness data and burden of disease.
* Case fatality (national and GBD study)
* Disability weight used in the GBD 2010 study

The NYCDOHMH previously estimated YLD based mainly on national rates where 1) YLD = (YLD/YLL from national study) * (YLL from NYC mortality data); 2) YLD = (YLD/YLL from national study) * (NYC population ). We should just repeat this with 2013 mortality data and 2010 rates. Where we can find them, we should also modify the prevalence data and other data elements for NYC.

3. **Costs**. The cost data merely need to be collected from literature reviews. To standardize these, we need to extract the total lost productivity and leisure time losses for active disease. These are then multiplied by median local wage for New York City and by the duration of the disease from the GBD study. Medical costs need to be separately extracted and adjusted to reflect NYC costs. We need to be careful to separate out studies that use charges from those that use costs. Those that use charges need to be adjusted to costs. My textbook has these tables in the back. All costs need to be adjusted to 2014 dollars using the consumer price index.

The Uniform Crime Reports has the total costs of incarceration. We need to figure out the percentage of these are linked to mental illness/substance abuse from the literature.

We need to get an estimate of social service utilization. I believe we can get these from Robin Hood.

4. **Program effectiveness**.  We need to obtain the cost of prevention programs and their impact on the duration of illness from Rufina Lee. We can’t get estimates of impacts on YLLs. In my opinion, we should assume that these are between zero and 100% and report them as a sensitivity analysis.



