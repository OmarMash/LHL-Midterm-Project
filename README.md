# LHL-Midterm-Project

## Problem
Everyone knows death is a part of life, but dying a preventable death or more specifically dying when doctors did not do everything they could to save you, will cause even more hardships and pain for their loved ones. And the #1 cause of death globally is cardiovascular diseases, which encompass many conditions including heart attacks, strokes, and the one we are gonna explore, heart failure. 

## Data

Up to date Data containing medical records of patients suffering heart failure were not easily accesible and open. That is expected becuase medical records contain very sensitive/personal information, and although Health care organizations are known to sell data after de-identifying the records, such Data would not be free nor easily accessible. The Dataset I found is from 2015 that contain data for 299 heart failure paitents. The Dataset contains 13 attributes which can be described by the table below. 

![Alt text](Variable%20descriptions%20for%20HF%20data.png)

## Cleaning Data

Data was fortunately already cleaned, only flaw I observe is the sex variable that containes a binary value does not denote what the binary value affirms. In this case it would be more reasonable to rename the variable male (AS 1 deonotes male). 

## EDA 
No clear trends or patterns that immediately catch viewer's eyes. The correlation map also doesnt indicate any clear relationship between variables, except for time and death_event variable (which has a negative moderate correlation). But EDA visuals are not strong enough of a basis to identify relationships.

## Statistical Modelling 

Using statistical modelling, We tried to figure out if the data can predict whether the patient passes away or not. Since the response variable is of a binary value, a logistic regression is reasonable. Modelling the data with a logistic regression and backward stepwise selection to find the model of best fit, we come to the conclusion that there are 4 significant independent variables. 

## A Potential Solution 
Now that we have figured out how to determine the possibility of a patients passing, what can we do with that information. One use case is offering a dashboard that reports weather the patient is a high risk or not to hospitals & Health care providers. They can use this dashboard to assess weather the patient is safe to be discharged or that he is a top proirity that needs to stay under a doctors supervision. 

## Important Note

The Purpose of this Project was not to research the metrics and possibilty of survival for heart failure patients. That would clearly need alot more research and studies. But to illustrate how we can leverage data to provide insights and solutions. 

