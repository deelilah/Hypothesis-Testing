# Hypothesis-Testing
This is a colab notebook containing tests done on the  Autolib electric car dataset to prove a null hypothesis.
REPORT ON HYPOTHESIS TESTING.
AUTOLIB ELECTRIC CAR SHARING

PROBLEM STATEMENT
BUSINESS UNDERSTANDING

Autolib electric car sharing was inaugurated in Paris in December 2011 and was closed within July 2018.The system entered service with a fleet of 250 blue cars and 250 rental stations servicing the city paris and 18 other surrounding communities.The purpose for having this vehicles is so they can be rented out since owning vehicles is costly and it was also a form of business for the rentees.

 DATA UNDERSTANDING AND DESCRIPTION

The data is from a source known as autolib which contains data on the Blue cars (dependent variables)that were used for renting,Utilib,Utilib 1.4 and some other object to define location and service port of the vehicles(independent variables).
The data contains 16085 rows and 13 columns.
The data contains certain variables that make it possible to derive data from it.eg.Postal code,the day type,the slots for charging the electric cars and the electric cars.
From the data I did cleaning which consisted detecting outliers by the use of interquartile range but chose not to remove outliers for it would reduce the accuracy of my data.
Data was collected from various sources including wikipedia.
I sampled the data that i used using the stratified sampling method for i required strata from different columns.

STATE THE HYPOTHESIS

A hypothesis being a prediction statement that requires variables and measurements on dependent and independent variables .I decided to major in the blue cars as my hypothesis and formulated a statement that states Blue cars are mostly used during the weekends.
Null Hypothesis - Blue cars are used more on weekends
Alternate Hypothesis - blue cars are not used mostly on weekends
The importance of this hypothesis is that it has put into consideration the dependent and independent variable and it is measurable with the data provided.

HYPOTHESIS TESTING
Having selected my criteria of interest which is the postal code,the blucars ,the day of the week.
I will filter the data to accommodate those columns consisting of the weekends and the other variables selected.
Calculate the sample mean of the blue cars i set aside.
Calculate the population mean for the weekdays
Check which statistical test to use.Most likely the t-test due to the availability of sample standard deviation and the  sample mean.
The alpha level i choose to use the common 0.05 that is mostly used when no significant value is stated.
Confidence level(1-0.05) is 95%

