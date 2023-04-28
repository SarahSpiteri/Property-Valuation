# Property Valuation Project

The tasks of this prject are devided across 4 main notebooks
1) Uses selenium to scrape a website that aggregates the listings from a number of real estate agents in Malta (only data in the quarter before the scraping data was used to have a valuation based on recent data)
2) Loop through the gathered listings to scrape further information about the properties
3) Cleans the data; this involves dealing with nulls, adjustments, cleaning property description text with lemmatization, and the creation of dummy variables from the listing description text
4) Employes a simple hedonic regression model to estimate the price of an example property

The third notebook makes use of some helper functions in TextFunctions.

This repository also includes the cleaned scraped dataset and the chromedriver used for the exercise.
