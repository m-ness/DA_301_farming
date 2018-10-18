# DA_301_farming

### Description:

The reason for this study was to find out what countries were producing and how that interacted with their population over time. There are many places that have serious food shortage problems so it is important to know where the food that is being produced is going and how it is being used.


The goals of this study were to find which countries produced the most; what the most produced item was; what was the difference in production between food and feed; when was there the most production. The variables that were examined and used were:

### Data:

Data for this study was gathered from [Kaggle.com](https://www.kaggle.com/dorbicycle/world-foodfeed-production) and from [WorldBank](https://data.worldbank.org/indicator/SP.POP.TOTL)

•	Area: County (173)
•	Item: Item produced (117)
•	Element: Food or Feed (whether the produce was used to feed animals or people
•	Year: from 1961 to 2013 (52 years)
•	Production: amount produced
•	Population: the population of any given country

### Explanation of the data:

Data for this project was taken from Kaggle which was initially procured from The Food and Agriculture Organization of the United Nations which provides free access to food and agriculture data for over 245 countries and territories. The data that was used contained: 

Columns for the country (174 countries);
the item that was produced (117); the Element of the item that was being recorded(Food - Human Food (Produce made for human consumption), Feed - Animal Feed (Produce made for animal production)); and a column for every year from 1961 to 2013 (52 years) with the amount produced by 1000 tons.

Another data set for Population was combined with the Production data that was taken from the World Bank Group from 1961 to 2013 which contained:

Columns for the Country name; the year; the population for that country in the given year.
The goal of this project was to find out what factors impact the production of a nation and why certain factors could play more of a role than others. These two datasets were organized by country and by year (in the case of the production it was also organized by item produced). They were then joined by the data in the production dataset, because the production dataset was the one the study was based off of. 

For the ease of graphing the data it was split into several subsets. Because of the large number of countries (174) and items (115) part of the data was then limited and grouped again into some of the highest producing nations (China, United States, Nigeria, India, Germany, Brazil, Denmark, Canada) with all of the possible items and the other part of the data set was grouped by highest produced items (Cereals, Milk, Starchy Roots, Vegetables, Maize, Sweet Potatoes, Fruits, Rice) with all of the countries still using them. Another dataset was made for the ease of regression as a subset that contained both the 8 countries and the 8 items. These variables (items and countries) were then made into Bernoulli variables with 1 meaning they were that item or country and 0 they were not.
