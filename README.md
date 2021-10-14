The goal of this project was to understand bias by looking through data on Wikipedia articles about politicians from a variety of countries. We used ORES to estimate the quality of the article.

Link to source data:
Populations by country data: https://figshare.com/articles/dataset/Untitled_Item/5513449
World population data: https://docs.google.com/spreadsheets/d/1CFJO2zna2No5KqNm9rPK5PCACoXKzb-nycJFhV689Iw/edit?usp=sharing

Politicians by country description (page-data.csv):
The data was extracted via the Wikimedia API using the associated code. It is formatted as a CSV and saved as page_data.csv in the "data" directory. Columns are:

1. "country", containing the sanitised country name, extracted from the category name;
2. "page", containing the unsanitised page title.
3. "last_edit", containing the edit ID of the last edit to the page.

World population data description (WPDS_2020_data.csv):
Data is from the world data sheet from PRB. Contains data about population metrics at different countries.
Relevant columns are:

1. FIPS - code describing the region
2. Name - country name
3. Type - granularity of region
6. Population - population at given region

Write up:
1. Before I started working on the data, I was thinking about access to technology. I suspected that countries with a higher poverty might also have a higher proportion of its population that are unable to access the internet, and therefore might have less articles written about their politicians. I also thought about government regulation. I know that in some countries, the internet is highly sensored, and there is less transparency in the affairs of the government. In these countries, I would also expect there to be a lower number of articles written about politicians. However, for the most part, I expect that if the assignment did not specifically ask me to do so, I would not think too much about the data in terms of bias, and this is something I should be more careful about in the future.

2. After conducting some analysis, unsurprisingly, many of the countries that ranked highly in terms of coverage had a low population density. Those that were larger, such as Iceland, were somewhat more prosperous countries that this is in line with my original hypothesis. Conversely, the bottom countries by coverage were south asian and asian countries with a high population density. North Korea, noteably is known for its media censoring, and this could be one reason that the number of political articles is low in this country as well. Unexpectedly, North Korea ranked very high in terms of percent quality, which means that although they did not have many articles about their politicians, the articles they did have were of high quality. Many counties did not have any good quality articles, which was surprising as well.

3. After this assignment I realized that there is a wide discrepency in the amount of quality information that is available. This information is unevenly distributed in terms of content. So it might be a lot easier to get information on one subject in one country, but almost impossible in others. Wikipedia as a data source is highly informative, but for this reason it should not be thought of as a one stop shop for all of our data needs. The information provided in wikipedia needs to be carefully weighed in terms of availability of reliable information in order to make a judgement on the conclusions found using the information.
