\# Movie Market Intelligence — Final Report



\## 1. Project Overview



This project demonstrates an end-to-end data analytics workflow using movie data collected from a public web-scraping practice source.



The project covers three CodeAlpha Data Analytics internship tasks:



1\. Web Scraping

2\. Exploratory Data Analysis

3\. Data Visualization



\## 2. Data Collection



Movie data was collected for the years 2010–2015 using Python, Requests, and a public AJAX endpoint.



A total of 87 movie records were collected.



\### Dataset Fields



\- `title` — Movie title

\- `year` — Year

\- `awards` — Number of awards

\- `nominations` — Number of nominations

\- `best\_picture` — Best Picture indicator



\## 3. Data Cleaning



The dataset was inspected for:



\- Missing values

\- Duplicate records

\- Data types

\- Boolean values



There were no duplicate records.



The `best\_picture` field contained missing values because the source only provided the field for movies marked as Best Picture. Missing values were converted to `False`.



The cleaned dataset was saved as:



`data/processed/movies\_clean.csv`



\## 4. Exploratory Data Analysis



\### Yearly Movie Distribution



The number of movies collected by year was:



| Year | Movies |

|------|--------|

| 2010 | 13 |

| 2011 | 15 |

| 2012 | 15 |

| 2013 | 12 |

| 2014 | 16 |

| 2015 | 16 |



2014 and 2015 had the highest number of movies in the dataset, with 16 movies each.



\### Awards Analysis



2012 recorded the highest total awards with 25 awards.



The other years recorded 24 total awards each.



\### Nominations Analysis



2012 recorded the highest total nominations with 75.



2013 recorded the lowest total nominations with 42.



\### Top Awarded Movies



The highest-awarded movie in the dataset was Gravity, with 7 awards and 10 nominations.



\### Awards and Nominations Relationship



The Pearson correlation between awards and nominations was 0.75.



This indicates a positive linear association between the two variables in this dataset. Correlation does not establish causation.



\### Best Picture



One Best Picture winner was identified for each year from 2010 to 2015.



\## 5. Data Visualization



The project includes visualizations for:



\- Number of movies by year

\- Total awards by year

\- Awards vs. nominations

\- Best Picture winners by year

\- Top 10 movies by awards

\- Total nominations by year

\- Awards and nominations by year

\- Correlation heatmap



These visualizations help communicate the main patterns and relationships identified during the analysis.



\## 6. Technologies Used



\- Python

\- Pandas

\- NumPy

\- Requests

\- BeautifulSoup

\- Matplotlib

\- Seaborn

\- Jupyter Notebook



\## 7. Project Outcome



The project demonstrates a complete data analytics workflow:



\*\*Web Scraping → Data Cleaning → EDA → Visualization → Insights\*\*



The resulting dataset, analysis, visualizations, and documentation provide a reproducible example of a practical data analytics project.

