# amazon-keywords-search-function
This is a simple function that can help you get a knit result about sales rank, reviews, reviews time and number.

this is a function built based on package : AmazonAPI, AmazonScraper and panda.
To run this function, you will need an amazon accesskey, amazon secret key, and an amazon associate id.

You can name your own keywords and number of records( the product number you want to see linked to the keywords)

The result of this function is two data frame:
a: the data frame contains each product's title , sales rank and it's url;
b: the data frame contains each product's title and the reviews and reviews time during last 12 month.
