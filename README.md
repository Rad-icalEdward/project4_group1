# Project 4 - group 1

## Project overview

Using a dataset solve, analyze, or visualize a problem using machine learning (ML) with the other technologies we’ve learned. Here are the specific requirements:

1) Find a problem worth solving, analyzing, or visualizing.

2) Use machine learning (ML) with the technologies we’ve learned.

3) You must use Scikit-learn and/or another machine learning library.

4) Your project must be powered by a dataset with at least 100 records.

5) You must use at least two of the following:

    * Python Pandas

    * Python Matplotlib

    * HTML/CSS/Bootstrap

    * JavaScript Plotly

    * JavaScript Leaflet

    * SQL Database

    * MongoDB Database

    * Google Cloud SQL

    * Amazon AWS

    * Tableau

## The data set

Using the following dataset charity_data, we will compare how effective machine learning is compared to other visualization tools.

## Project outline 

We will be focussing our findings on answering the following questions:

Tableau shows us that around 75-80% of campaigns were classified as successful, so how can machine learning make this % better?

What will machine learning do to predict a successful campaign?

Can machine learning predict a higher success rate? If so then what do the successful campaigns need?

Is the succes rate prediction in machine learning the same as what the data in Tableau has shown?

## Data clean up

The data set contains over 34,000 rows of data and all rows contain the relevant information. The only initial clean up that was needed involved changing a those rows that contained the 'date' Jan-99 in the Income_Amt column. The data contained in this is a range of numerical data. So using Excel find and replace, Jan-99 was replaced with the income range 0-1999. Over 700 rows were amended.

## Analysis

[**Tableau dashboard story - HF**](https://public.tableau.com/app/profile/hayley.fuller/viz/Project4-Charitydata/Charitydataanalysis)

**Analysis of charity data using Tableau - HF**

This dataset from Alphabet Soup contains 34, 299 applications. Of those applications the majority of campaigns were successful.

The successful campaigns are classified as a Trust. With 75.61% of overall successful applications. Compared to a Corporation which amounts to 0.18% of overall successful applications.

![plot](Images_HF/Successful_data.png) 

The amount asked for from these successful campaigns classified as a Trust organisations is 30, 456, 770, 364 that is 75.61% with only 13, 808 of the 34,299 applications.

The money is being used for preservation of the charity that is applying. This makes preservation the top reason for charity applications at 84.55%, with only 8,380 of the overall applications.

This dataset shows us the income amount of the charity. And the more successful applications are charities with an income of 25,000 to 99,999, with preservation as the reason.

Looking at the amount asked for in relation to the income amount we see that those with a higher income 50M+ ask for more compared to those with a lower income amount. This is not surprising as it is to be expected that those with a higher income need more to sustain their charity.

**Overall conclusion is that for a campaign to be successful they need to have the following attributes…**

1.	Have an income amount of 25,000 to 99,999
2.	Be needing the money to preserve the charity
3.	And be a Trust, rather than an Association, Corporation or Co-operative

**Analysis of charity data using Tableau - LR**

WRITE FINDINGS HERE

**Analysis of charity data using Machine Learning - AG, JB & DL**

WRITE FINDINGS HERE

## Limitations regarding the data set

1) This is existing data

2) There are no dates regarding when funding was granted
