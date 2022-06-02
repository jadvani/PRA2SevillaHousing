# Sevilla Housing
 A study about Seville's House Prices
 
## Context
 
 Based in the Boston Housing dataset, I was wondering to create a similar amount of fresh houses for sale based on real (and current) information from my home city, Seville (Spain).


## Content

This dataset contains 1844 houses announced in May 2020. Please, note that some of the houses might be duplicated, as sometimes the seller publishes the same house twice with a slightly different amount. An interesting idea to clean the data before using would be to check if some of the fields or the whole row appeared before.

Some details about the fields included:

The 'title' field contains a first word explaining if the row describes details for an appartment (piso) or a House (casa). This can be useful to get a new information column.

The column 'price', must be multiplied by *1000 and is in € (euros), the currency currently used in Spain.

The year of construction was not included in all of the adverts, so the ones without this information field were marked as 0.

There was no public information related to criminality statistics, so I came up with the idea that the neighbourhoods with less hotels would be the most dangerous ones (or at least the less attractive).
The number of hotels for each neighbourhood was extracted from http://www.hotelsearch.com/

A house includes garage when the field value is set to 1. The same idea has been applied to the 'terrace' field.

## Acknowledgements

All these houses information has been extracted with data scraping techniques from Idealista website.

