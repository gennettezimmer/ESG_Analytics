# ESG_Analytics

Source data: 

1) MSCI ESG Ratings Data for over 15000 corporates as of March 2022. https://www.kaggle.com/datasets/debashish311601/esg-scores-and-ratings,
2) Country code spreadsheet - https://github.com/lukes/ISO-3166-Countries-with-Regional-Codes/blob/master/all/all.csv
3) GDP - https://en.wikipedia.org/wiki/List_of_countries_by_GDP_(nominal)

Methodology:

Consulting with a professor at Northeastern University to present industry insights as a guest speaker for a graduate level Global Studies course on
Sustainable Development. Project involves demonstrating data analytics methods to derive insights using Python. Desired outcome is for students to
understand the role of machine learning to determine predictability of Ovearall ESG Scores and compare variables to derive insights through visualizations
on the potential impact ESG ratings from global, enconomic, political and social perspectives. 

Initial research in GOZ_ESG_Analytics.ipynb used data for all 15,644 companies in order to get an understanding of the data, determine what questions might
be asked and how they would be presented. Once a direction was determined, ESG_Analytics_for_Food_Related_Sectors.ipynb focuses the research and
conclusions specifically on food related sectors comprising of 745 companies.  Specifically - Beverages, Food Products, Retail - Food & Staples, and
Restaurants.

Findings are limited by the fact that the data only contains the final ratings for each company on an overall basis as well as an environmental, social and
governance basis. Questions asked to determine ratings and how data was weighted to come to the overall score was not available.


Sections - ESG_Analytics_for_Food_Related_Sectors.ipynb:

1) Install Packages and Mount Drives
2) Exploratory Data Analysis (EDA) - Overall
3) EDA for Sector focused research - Food and Beverage
4) Hypothesis testing
5) Histogram Comparison of Scores for Food related sectors
6) Line Graphs Comparisons for Food related Sectors
7) Predictive Modeling
