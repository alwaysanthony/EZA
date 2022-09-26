# Houston House Price Prediction

## Topic 

We've chosen to analyze and construct a predictive model for housing prices in Houston, TX (MFU/SFU), as well as determining and describing the relationship between the final price and its various input factors.

Given the broad public consensus regarding the instability of the Housing market nationwide, we've chosen this topic in order to determine potentially causal trends and correlations betweeen property metacharacteristics, and to help inform the decision making process for a group member currently seeking to purchase a property in Houston.  

## Data 

The data we will be performing analysis on, and which we will use as ML model inputs will consist of the following fields:

- Super Neighborhood Median Household Income
- Super Neighborhood Population
- Square Footage
- Number of Bedrooms
- Single Family vs Multi-Family
- Zillow Walk Score
- Zillow Transit Score
- Zillow Bike Score
- Property Price

Data regarding Super Neighborhoods will come from the Houston, TX 2015 Census data, and the follow on demographic descriptions of each Super Neighborhood
as provided by Houston's city website (https://www.houstontx.gov/planning/Demographics/docs_pdfs/SN/Median-Household-Income.pdf).

The remainder of the data will be gathered by scraping the Zillow listings website for all relevant information. The scraping code is included in the repo.

The placing of these properties into their respective super neighborhoods will be accomplished through a pipeline which utilizes GIS representations of Super Neighborhood boundaries from the 2010 census, which upon checking, is still relevant and accurate to their contemporary states (https://koordinates.com/layer/12942-houston-texas-census-by-super-neighborhood-2010/)
 
## Questions We Can Answer

With this data, we will be able to determine which input factors are most correlated/impactful vis-a-vis final property price, as well as which locales and property characteristics are ideal for purchasing a new property in Houston, TX.

## Group Members

- Ashlē Mercer
- Anthony Nguyen
- Henry Hawgood
- Jose Espinosa-Tello
- Samantha Neal

## Communication Protocols

Team members are connected via Slack within a group chat, and in addition to daily updates on the status of each member's assigned project coverage, further meetings are arranged and prosecuted as issues, novel information or factors, and new objectives manifest.

## Technologies
We will use PostgreSQL to set up our database. From here our ML model will be able to take in data and predict prices.

## Presentation 

Link to our Google Slides Presentation:

https://docs.google.com/presentation/d/1cdkoQS5zwdwTWxeuK_wTwghmi5nbepGc9ujuVGhdKTY/edit?usp=sharing
