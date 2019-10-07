## AirBNB analysis

## Motivation

Come up with valued business questions that could be answered by data science skills using historical data.
Use visualizations to make findings more understandable and communicate to stakeholders from different backgrounds.

## Business questions being answered

How is the pricing differ across airbnb?
Which Feature affect listing price the most in Seattle, and how?
What are the most important things to tenants?


## Data

1. "calendar.csv" :: with columns of {"listing_id","date","available","price"}, it tells the price and availability of each AirBNB house on each day.
2. "listings.csv" :: It has more than 80 columns and tells everything about each AirBNB house. Like ratings, descriptions, basic room layouts etc.
3. "reviews.csv" :: It collected every verbal comments tenants made online, with columns {"listing_id","id","date","reviewer_id","erviewer_name","commnets"}.


## Analysis

As there is no modelling work in this analysis. All efforts are to data cleannign and exploration to answer business questions raised above. And most data wrangling work is put on "listing.csv". Missing values are interpolated or dropped based on my judgements. Histogram, and wordclouds are adopted to better visualize the results.

## File descriptions

This project contains following directories and files.

```text
AirBNB/
├── AirBnbSeattle.ipynb
└── data/
    ├── calendar.csv
    ├──	listings.csv
    └── reviews.csv
```

- AirBnbSeattle.ipynb  ==> Notebook to investigate trends of bookings on Airbnb in the year 2016 in Seattle.
- calendar.csv         ==> Booking information of houses in Seattle.
- listings.csv         ==> Information of houses in Seattle.
- reviews.csv          ==> Reviews of houses in Seattle.


# Blogpost on the findings
https://medium.com/@subramanian.kishore/airbnb-seattle-listing-analysis-f5f2917699bc
