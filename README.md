# Analysis of Turkish Cities

## Goal

The goal of this project was to extract, process, and analyze data on the changing population sizes of Turkish cities with populations over 7,000

## Relevant Documentation

https://www.crummy.com/software/BeautifulSoup/bs4/doc/

https://pandas.pydata.org/docs/

https://docs.scipy.org/doc/scipy/

https://matplotlib.org/stable/index.html

## Licenses

This project is covered by the MIT License. The source data, which was scraped from Wikipedia, is covered by the Creative Commons Attribution-ShareAlike License (CC-BY-SA).

## Data Attributes

- Rank: int64, where the city ranks in terms of population estimate in 2015
- City or Town: object (string), name of the city or town
- 1990 Census: int64, population of the town recorded in the 1990 census
- 2000 Census: int64, population of the town recorded in the 2000 census
- 2007 Estimate: int64, estimate of the town's population in 2007
- 2008 Estimate: int64, estimate of the town's population in 2008
- 2015 Estimate: int64, estimate of the town's population in 2015
- Province: object (string), name of the province in which the town is located
- Percent Change: float64, estimated percent change in the town's population from 1990 to 2015

## Potential Issues

There are no clear sources of bias in this data.

## Provenance

The data was sourced from this web page: https://en.wikipedia.org/wiki/List_of_largest_cities_and_towns_in_Turkey
