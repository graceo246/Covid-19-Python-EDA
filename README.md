# Covid-19-Python-EDA

## Overview

This project provides an exploratory data analysis of COVID-19 data, aiming to derive insights into the pandemic's impact across various regions and populations. The analysis answers key research questions regarding recovery rates, death-to-recovery rates, and the relationship between testing and case severity.


## Technologies Used

**Python**: Python is used for data cleaning and preparation using Pandas, matplotlib and numpy.


## Project Files



1. worldometer_data.csv: The unprocessed Covid 19 dataset.

2. Covid19EDA.ipynb: Google Colab containing the Python code for data cleaning and analysis.


## Data Cleaning Process

The detailed data cleaning process, including the following steps, is documented in the Jupyter Notebook (Covid19EDA.ipynb):

1. Importing the raw COVID-19 data.

2. Correcting data types 

3. Handling missing values.

4. Managing columns


## Questions for Analysis
1. What is the global recovery rate? recovered/total cases?
   
2. How does the death to recovery rate vary across different countries/countinents? Do countries with more tests per million population have better recovery rates?

3. Are densely populated countries more vulnerable to higher serious cases than less populated countries?

4. Does the number of tests per 1m correlate with lower death rates?

   
5. Do regions with high cases per million also experience higher serious/critical cases, and how does this relationship vary based on population density?


## Results

### What is the global recovery rate (%) by continent?


The global recovery rates varied by continent, with the following results:

Africa: 69%

Asia: 75%

Australia/Oceania: 58%

Europe: 53%

North America: 53%

South America: 69%

This indicates that Asia had the highest recovery rate, while Europe had the lowest.

### How does the death-to-recovery rate vary across different countries/continents? Do countries with more tests per million population have better recovery rates?



The death-to-recovery rates were as follows:

Europe: 13%

North America: 7% 

South America: 5%

Africa: 3%

Asia: 3%

Australia/Oceania: 2%


Continents such as Asia (71,053 tests per million) and Europe (average of 172,628 tests per million) have higher testing rates. It is quite shoccking that Europe have such a high percent of death-to-recovery rate despite the continent ranking 4th in overall cases, this could suggest other continents have more effective healthcare options, faster detection of Covid-19 and many more.

### Are densely populated countries more vulnerable to higher serious cases compared to less populated countries?

Analysis revealed average serious/critical cases by population categories:

Very Low Population: 21 cases


Low Population: 204 cases


Medium Population: 2,310 cases


High Population: 8,944 cases


This indicates that countries with higher populations tend to experience more serious/critical cases, suggesting a correlation between population density and the severity of cases.


### Does the number of tests per 1 million correlate with lower death rates?


Tests per million and deaths per million had a correlation coefficient of 0.13, suggesting a somewhat favourable relationship. This implies that although a relationship might exist, it is not very strong and that death rates are probably influenced by other variables. The weak correlation suggests that death outcomes may not be greatly impacted by merely raising testing rates. This might point to several underlying factors




### Do regions with high cases per million also experience higher serious/critical cases, and how does this relationship vary based on population density?


The research revealed a slight positive trend with a correlation coefficient of 0.22 between instances per million and serious/critical cases. A possible correlation between the two variables was suggested by the scatter plot with a trendline, which showed a steady rise in serious/critical cases as cases per million increased, especially for nations with more than 40,000 instances per million.


## Follow-up questions

1. What other factors might influence the relationship between tests per million and death rates?

2. What are the healthcare challenges faced by Europeans that could explain the high death-to-recovery rate despite having advanced healthcare systems?

3. How do socioeconomic factors vary across continents and influence recovery rates?

