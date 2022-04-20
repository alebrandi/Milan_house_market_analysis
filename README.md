# Milan_house_market_analysis
Analysis and prediction of the housing market for the city of Milan, Italy 

## Author
- [@alebrandi](https://www.github.com/alebrandi)

## Summary

For this project I first had to scrape the data of all the houses for sale in the city of Milan, Italy. I chose this city because it is one of the richest and largest cities in my country and where the housing market has lately skyrocketed. 
To do this I used the platform https://www.immobiliare.it/ which is the most famous website for selling and buying properties between private individuals in Italy.

Instead of using Scrapy or Bs4 to scrape the data, I managed to find the API endpoint of the website. To do this you just have to inspect the website, click on the Network tab and go through all the Fetch requests until you hopefully find the one that previews the contents of the page in json format.

Once I had the data, I formatted the most useful information in a Pandas Dataframe, I then performed some data analysis and, after that, I attempted to predict the house pricing based on the features of the property.
