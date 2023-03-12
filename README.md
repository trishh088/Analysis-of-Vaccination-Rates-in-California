# Analysis of Vaccination Rates in California

### Problem Statement

I tried to analyze vaccination rates in California schools and school districts using various statistical tools
on Time series data from the World Health Organization which reported the vaccination rates in the U.S. for five
common vaccines and California public school districts from 2017 along with data from about
7,381 individual schools. Given the world’s recent exposure to COVID-19, we know now more than ever how
vaccinations can curb the spread of virus and saves lives, and in this project I analyzed and saw how
different factors like poverty, religion, medical factors affect vaccinations.
The whole analysis was conducted using R programming using R-studio.


### Analysis

The following steps were followed to generate the report which can be found in the [PDF](https://github.com/trishh088/Analysis-of-Vaccination-Rates-in-California/blob/main/Final%20Report.pdf)

1) I did Exploratory Data Analysis to understand the data provided and check if there are any outliers, nulls, skewness, normality or correlation that can affect the analysis for both the delimited data frame and the time series data frame.
2) I removed outliers, skewness to make sure that the data is normal and checked correlation for the delimited data frame and removed trend and cyclicity in the time series data frame.
3) Tried to answer multiple questions such as - mean U.S. vaccination rates from recent years, among districts, how are the vaccination rates for individual
vaccines related?, how do these Californian vaccination levels compare to U.S. vaccination levels etc. using frequentist and Bayesian tests.

### Conclusion
Considering all the models I built, be it frequentist or Bayesian, I saw that the results from both were matching, reinforcing confidence in the results. 
First I saw that if a student took one vaccine, there is a high chance that they took all the other vaccines like Polio, MMR, DTP, HepB. 
I also saw that having rules mandated in states affects the vaccination rate in a positive way and that belonging to a district which is below poverty line, there is a boost in vaccination probably. I could see that in the recent years the vaccination rate was pretty much constant.

I got the below observations from our analysis/conclusion: 

1. Public schools were the major ones that reported their vaccination data and since they are funded by the state, the state legislator’s office should
allocate financial assistance to school districts as they will not only help eradicate or avoid an epidemic but also help students which come from low economic backgrounds to get the necessary vaccinations. 

2. Since the state would be funding these schools they can even get compliance on reporting of vaccination records from atleast the public schools. 

3. Families in the below poverty district affected negatively meaning, the income didn’t affect their will to get their children vaccinated which could be because they go in state funded schools so they don’t have to pay for the vaccination. 

4. Families who enrolled their children in school didn’t want to take the belief exempt as maybe since the parents are educated they know that vaccination is
important. 

5. Families below poverty line preferred to get the vaccination and same is the case with enrolled students where we saw that such children had their vaccination up to date. 

6. We could see that the interaction between PctChildPoverty and Enrolled was not significant.

