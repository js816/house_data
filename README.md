# King County Housing Data Visualization

[Tableau Public Visualizations](https://public.tableau.com/app/profile/josh.stephens6499/viz/king_county_house_data/KingCountyHomesDataset?publish=yes)

## Purpose
The purpose of this project was to practice visualizing data in various ways using Tableau.  The dataset contains various features related to house sales in King County from 5/2014-5/2015.  The dataset and additional details can be found on [Kaggle].( https://www.kaggle.com/harlfoxem/housesalesprediction)

## EDA and data cleaning
Some EDA and cleaning were performed using Python and Pandas.  Unneeded columns were dropped.  
For ease of visualization, some columns were converted to thousands of dollars.  House sales price, lot sq ft, and living sq ft were all converted to thousands of dollars to allow for cleaner visualizations.  While this could also have been done later in Tableau, in this project new columns were created and the original columns were dropped.
A cleaned csv file was created.  

## Visualizations
The cleaned CSV file was used to create visualizations in Tableau Public.  Screenshots of some images are below and the interactive visualizations are available [online](https://public.tableau.com/app/profile/josh.stephens6499/viz/king_county_house_data/KingCountyHomesDataset?publish=yes).  

## Findings

### Average sales price
Overall, the average sales price in the dataset was $540,000.  The map below visualizes the average sales price by ZIP code

![image](https://user-images.githubusercontent.com/82730954/146038548-4c1eeeb5-0baa-47e8-9a82-8810f0825de4.png)

### ZIP codes with higher priced houses

This map shows those ZIP codes with average sale prices > $750k

![image](https://user-images.githubusercontent.com/82730954/146060458-f86aada9-1f19-4131-8104-16912407374d.png)


### Homes in dataset by ZIP

Overall, there were 21,613 homes in the dataset.  The following map shows the distribution by ZIP code

![image](https://user-images.githubusercontent.com/82730954/146060586-8be4f99e-fc23-42bf-8794-fdcb6008b740.png)


### Average price vs. number of bedrooms

The chart below shows the average price of houses by the number of bedrooms.  The chart defaults to 1-5 bedrooms but this filter can be adjusted on the Tableau Public site.

![image](https://user-images.githubusercontent.com/82730954/146060794-caf42968-2f15-41ae-8f70-dcb8a7631bfa.png)


### Average price vs. number of bathrooms

This chart visualizes the average sale price by the number of bathrooms.  The default range is 1-4 but this can be adjusted on the interactive site.  Hovering over a bar also shows the count of homes for each category.  For example, only 9 homes in the dataset had 1.25 bathrooms.  These homes had an average sale price significantly higher than the nearly 4,000 homes that had 1 bathroom.

![image](https://user-images.githubusercontent.com/82730954/146061010-00366ddb-86b2-442c-b1cf-ba700b4ed657.png)

