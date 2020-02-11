# Pricing_Airbnb

Motivation
“How much is my property worth?” is a recurring question in the space of real estate. Finding competitive pricing for property leasing and sales is essential to both households and businesses in the advent of needs such as relocation or simply seeking an alternative revenue stream as property holders.

The Opportunity
In this paper, our team seeks to explore a new way to approximate the best price for a property by using predictive tools. Our objective is to obtain a model that can output an “expected market value” of a property based on some features and fields (physical or non-physical). We believe this generalized approximation can be done by training the model on open market data and pricing points of past openly traded properties. We see the “expected market value” as not only a reference point for the value of the house, but also a point of opportunity for undercutting the market, thereby gaining a competitive advantage over other competitors.

Secondary Objectives 
Apart from the aforementioned primary goal of constructing a predictive model to gauge the expected market value of a property, we also carry two secondary goals that we examine in the project.
 
Influences Across Years	
We want to examine the factors 	affecting property prices, specifically regarding how they’ve changed over recent years and across different metropolitan areas. With this goal in mind, we anticipate an opportunity to forecast the future trend of the property industry and offer tailored recommendations to future property owners.

Non-Physical Features
We want to determine whether or not contemporary housing prices are affected by non-physical house related features, such as the status of the renter or hosts and qualitative description attached for a listing. With this goal, we seek to better understand current property market in relation to non-traditional brick and mortar factors and construct a nuanced strategy on how to further create value out beyond the physical build of a property.

The Data Source 
We obtained our data from the Airbnb housing dataset provided on Kaggle. The dataset selected is a great simulation of the market condition - rational actors, no monopolies, etc. -  that is needed for us to make a fair expected value calculation. The dataset contains 74,111 properties and 29 columns. It has a series of relevant information, that caters to our investigative goal:
physical features of the property, including its type and number of bedrooms
rental information, such as whether or not it’s on a per room basis or whether or not it has a cancellation policy
host information, such as whether or not he/she is verified
location information by city and GPS.
The data also span across 9 years from 2008 to 2017 in 6 major US cities.

Paper Flow 
This paper will start off with a section of exploratory data analysis focusing on the inferences of the secondary goals, followed by a process of detailed model construction where we will employ standard modelling and evaluation strategies. The report will conclude with a final interpretation of results and recommendations to relevant stakeholders in the industry.
