# Review Stuffing Services - A quick Analysis

## Motivation
I encountered an advertisement for review stuffing services, and thought it would be fun to check whether such services could conceivably have an impact on actual business. At that time, I was pursuing a Udacity Data Scientist nanodegree, and the project synergised well with a an AirBnB dataset I was playing around with. 

I have a blog post on this [here](https://link.medium.com/B1opXtwtZ9), if you want to read more. 

### Key Questions Asked :  
The review stuffing service provided "guaranteed SuperHost status" along with "hundreds of 5 start reviews". So, my questions 

1.) Does achieving the SuperHost status enable you to charge more for your properties?  
2.) What about Neighbourhoods? Do they affect pricing ?  
3.) What about review boosting services? Are they worth your time ? Do having higher ratings help you charge more ?  

Due to time constraints, these questions are left for the future :

4.) How is occupancy as an earning factor to decide Superuser badge value?  
5.) Which keywords will help attract more visitors to your listing?  
6.) What about frequescy of updates? Does it influence customer selection ?  
7.) Pictures : Do large pictures help in getting more customers ? 

## Files Included  
1.) Seattle Listings Airbnb.csv : The main data file with the data used in the analysis  
2.) Howtoearnmore.ipynb : A jupyter Notebook file with code exploring the first three questions  

## Prerequisites
### Languages :
Python 3

### Libraries
Pandas
Plotly
Numpy

### Optional
Jupyter Notebook

## Summary of the Results :

1.) Does achieving the SuperHost status enable you to charge more for your properties?  
Result : Wonders of wonders ! A visualization does support the assertion that having a superhost status does enable you to charge more for your properties. 
**But** : There are a lot of factors assumed equal here : We are not accounting for price variability caused by Neighbourhoods, extra amenities provided or simply, better and larger properties. **Further analysis (see below) paints a conflicting picture**. Thus, the superhost status seems to be a relatively minor factor in pricing  

2.) What about Neighbourhoods? Do they affect pricing ?  
Result : **Very much so** ! The graph shows a wide range of pricing, making clear that neighbourhoods may be the most important pricing factor. This can be relevant when making real estate purchase decisions, and help decide a fair price.  

1 + 2.) Lets take a look at the neighbourhood effect on the superhost badge "value", taking a single neighbourhood.    
Result: We only look at one neighbourhood - West Queen Anne - here, but that immediately points out a different scenario as compared to the assertion above. Therefore, one cannot conclude that the superhost badge will enable a host to enjoy higher pricing for his properties.  

3.) What about review boosting services? Are they worth your time ? Do having higher ratings help you charge more ?  
Result: Generally more positive reviews do seem to trend towards higher pricing, so review boosting services may be worth paying for, if extremely unethical and running afoul of the AirBnB terms and Conditions. It may be just better to solicit positive reviews from guests.  


## Authors
Aditya Nawalgaria

## Acknowledgments
The team of the [Udacity Nanodegree program](www.udacity.com)  
The team of [AirBnB](https://www.kaggle.com/airbnb/seattle/data) for the dataset, and [Kaggle](https://www.kaggle.com) for hosting it
