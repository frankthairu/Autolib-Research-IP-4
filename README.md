
# Autolib-Research-IP 4

This is a research i carried out about autolib cars

# Overview

Autolib' was an electric car sharing service which was inaugurated in Paris, France, in December 2011. It closed on 31 July 2018. It was operated by the Bolloré industry and complemented the city's bike sharing system, Velib', which was set up in 2007. The Autolib' service maintained a fleet of all-electric cars which included the Blue cars, the utilib cars and utilib 14 cars for public use on a paid subscription basis, employing a citywide network of parking and charging stations.

Just like before, we have been tasked to understand electric car usage by solving for another research question. We will work as a Data Scientist for the Autolib electric car-sharing service company to investigate a claim about the blue cars from the provided Autolib dataset.

In an effort to do this, we need to identify some areas and periods of interest via sampling stating the reason to the choice of method, then perform hypothesis testing with regards to the claim that we will have made. Our claim which we have been asked to look into is that no. of cars taken in area postal code 75015 is greater than that of area 75017

###### To work on this project, we will perform the following analysis with Python; 

1. Find and deal with outliers, anomalies, and missing data within the dataset.

2. Plot appropriate univariate and bivariate summaries recording our observations.

3. Implement the solution by performing hypothesis testing.


Below are the guidelines for creating my report:


###### Problem Statement

The claim that we are working on is that more blue cars were taken in Postal code 75015 compared to 75017.
Thus , our null hypothesis will be that more blue cars were taken in Postal code 75015 compared to 75017

###### Data Description

The Dataset we will be using is an autollib dataset, which involves different sets of cars i.e Blue cars, the utilib cars and utilib 14 cars that were used in the France region. The dataset contains information from different areas with different postal code.

###### Sampling Methodology

In our reasearch, since we are interested in carrying out the hypothesis between two different areas i.e postal code 75015 and 75017, we will use the stratified method. This is most efficient method since the postal codes will be our strata.

We we also only be using data from the blue cars only

###### Hypothesis Testing

We will be using the z_test to carry out our Hypothesis testing since we are relating to a ample of grater than 30 i.e (n>30) In our case, we will be using a sample of 70.

Its also a convenient method since we know our standard deviations and mean.


A z-test is also useful when we want to determine whether two population means(in our case data from different postal codes)are different when the variances are known and the sample size is large.

In our z_test we will be looking at blue cars taken and comparing it with the two postal codes i.e codes 75015 and 75017.

Our argument is that more blue cars were taken in Postal code 75015 compared to 75017.

Thus , our null hypothesis will be that more blue cars were taken in Postal code 75015 compared to 75017.

If we obtain different results, we will have reject the null hypothesis and accept the alternative hypothesis.

###### Hypothesis test results

After performing our hypothesis testing using the z test meyhod, we found out that we have to reject the null hypothesis since the p value was way less than our signifacnt level. 

This means that our null hypothesis which states that more blue cars were taken in Postal code 75015 compared to 75017 is false


###### Summary and Conclusions

After succesfully perfomring our project which included sampling followed by a hypothesis testing, we came to a conclusion that more blue cars were taken in the area of postal code 75017 compared to that of postal code 75015


The dataset and glossary to use for this project can be found here [http://bit.ly/DSCoreAutolibDataset] and here [Link] respectively.

The provided dataset is a daily aggregation, by date and postal code, of the number of events on the Autolib network (car-sharing and recharging)


