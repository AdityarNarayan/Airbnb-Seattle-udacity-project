### Airbnb-Seattle-udacity-project
Table of Contents
1. [The Libraries That I Have Used](https://github.com/AdityarNarayan/Airbnb-Seattle-udacity-project/blob/master/README.md#the-libraries-that-i-have-used)
2. [Business Problem](https://github.com/AdityarNarayan/Airbnb-Seattle-udacity-project/blob/master/README.md#business-problem)
3. [File Descriptions](https://github.com/AdityarNarayan/Airbnb-Seattle-udacity-project/blob/master/README.md#file-discriptio)
4. [Summary Of The Results](https://github.com/AdityarNarayan/Airbnb-Seattle-udacity-project/blob/master/README.md#summary-of-results)
5. [Blog on Airbnb-Seattle-udacity-project](https://medium.com/@adityananda14/a-deep-dive-into-seattle-airbnb-market-data-science-project-4c57f35eb322?source=friends_link&sk=5f05da5f364eb59db815a2fb0be69c43)
6. [Acknowledgements](https://github.com/AdityarNarayan/Airbnb-Seattle-udacity-project/blob/master/README.md#acknowledgements)

### The Libraries That I Have Used
The project was implemented using Anaconda distribution of Python 3.0. Moreover I have used the following python libraries:

1. Collections
2. Matplotlib
3. NumPy
4. Pandas
5. Seaborn
6. Sklearn

### Business Problem

I have tried to find below answers for the below questions.

1. How does the pricing increase or decrease by season?
2. What is the peak season in Seattle?
3. How does the pricing increase or decrease by neighborhood?
4. Which ones are the priciest neighborhoods in Seattle?
5. How does property types within neighborhoods impact price for the most expensive neighborhoods and most common property types?
6. Can we predict a price for a given listing?
7. What factors of the listing correlate best for predicting the price?

### File Discription
The Jupyter notebook showcases the analysis done in order to explore the dataset, the data prepartion and wrangling as well as the building of prediction models in order to answer the questions above. The notebook contains markdown cells to help with documentation of the steps as well as to communicate findings based on each analysis.

For reference an HTML version of the notebook is also available.

Lastly, the seattle folder contains the dataset from Kaggle (https://www.kaggle.com/airbnb/seattle). It contains 3 files:

1. calendar.csv: calendar availability of listings and price
2. listings.csv: information about all the available listings
3. reviews.csv: listing reviews by the users

### Summary Of Results
The following key findings from the analysis are summarized below:

1. It was found that the peak season in Seattle is during the summer months from June to August, with the absolute peak being in July.
2. The "Southeast Magnolia" neighborhood was the priciest neighborhood in Seattle, followed by Portage Bay. Rainier Beach was the cheapest.
3. Looking further at neighborhoods and property types, I found out that houses in Portage Bay are the most expensive followed by houses in West Queen Anne and Westlake.
4. Using LinearRegression, I was able to predict price based on a prepped and cleaned dataset, with an r2score of 0.62 on both training and test datasets.
5. It was found that the features that had the most impact on price were a combination of host details as well as descriptive information about the listing.

### Blog on Airbnb-Seattle-udacity-project
I have written a blog on website Medium about the project and observations. Link is down below
https://medium.com/@adityananda14/a-deep-dive-into-seattle-airbnb-market-data-science-project-4c57f35eb322?source=friends_link&sk=5f05da5f364eb59db815a2fb0be69c43

### Acknowledgements
Credit to the AirBnB dataset published by AirBnB and Kaggle for hosting it, the dataset here: https://www.kaggle.com/airbnb/seattle

