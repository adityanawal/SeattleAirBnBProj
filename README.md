# SeattleAirBnBProj

This project deals with taking some Seattle AirBnB data and doing some basic data visualizations to see if one can find a way to charge higher prices and earn more by focusing on particular aspects of his or her AirBnB host profile. The project is exploratory in nature, and will continually be updated with different metrics which one can focus on.

### Key Questions answered :  

1.) Does achieving the SuperHost status enable you to charge more for your properties?  
Result : A visualization does support the assertion that having a superhost status does enable you to charge more for your properties. However, there are a lot of factors assumed equal here : We are not accounting for price variability caused by Neighbourhoods, extra amenities provided or simply, better and larger properties. Further analysis paints a conflicting picture. Thus, the superhost status seems to be a relatively minor factor in pricing  

2.) What about Neighbourhoods? Do they affect pricing ?  
Result : Very much so ! The graph shows a wide range of pricing, making clear that neighbourhoods may be the most important pricing factor. This can be relevant when making real estate purchase decisions, and help decide a fair price.  

1 + 2.) Lets take a look at the neighbourhood effect on the superhost badge "value", taking a single neighbourhood.    
Result: We only look at one neighbourhood - West Queen Anne - here, but that immediately points out a different scenario as compared to the assertion above. Therefore, one cannot conclude that the superhost badge will enable a host to enjoy higher pricing for his properties.  

3.) What about review boosting services? Are they worth your time ? Do having higher ratings help you charge more ?  
Result: Generally more positive reviews do seem to trend towards higher pricing, so review boosting services may be worth paying for, if extremely unethical and running afoul of the AirBnB terms and Conditions. It may be just better to solicit positive reviews from guests.  

#### Questions for the future :  

4.) Take a look at occupancy as an earning factor to decide Superuser badge value  
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

## Authors
Aditya Nawalgaria

## Acknowledgments
The team of the Udacity Nanodegree program  
AirBnB for the dataset, and Kaggle for hosting it
