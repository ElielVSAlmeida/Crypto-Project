# Welcome to the Crypto Project!

First of all, this project aims to show a sample of the abilities in web scraping and APIs with **BS4** and **Requests**, for operation optimization it was used **OS**. The goal is not only data scraping but understanding the **Fluctuation Patterns** and how the fluctuation varies across time to back-up investment decisions with **Data Analysis** and **Sentimental Analysis**. Also first step experiments with **SKLearn**, **ARIMA** and **Auto-Arima**.The data was cleaned and formatted with **Pandas**, and **Matplotlib** was used for visualization. Hypothesis:

- Some weekdays, more than others, mark the weekly peak and bottom occurrences.

- Some months, mark the yearly peak and bottom occurrences more frequently.

- The effect news can display on price fluctuation in the short term.


# Data Sources

- **Webscraping**

We used FINANCE.YAHOO.COM to get data - we were searching for a specific block of information named “candle” - and through this website we were able to find data from 2014 until the present date.

- **API**

After trying the NEWS API and failing because it only retrieved 1 month old news, we tried to use GoogleNews, but we soon reached the limit of the free plan. We had success using the NEWS API by MatcherLabs.
	
## Study 1

![alt text](https://github.com/ElielVSAlmeida/Crypto-Project/blob/main/Graphics/study1.png)

## Study 2

![alt text](https://github.com/ElielVSAlmeida/Crypto-Project/blob/main/Graphics/study2.png)

## Study 3

![alt text](https://github.com/ElielVSAlmeida/Crypto-Project/blob/main/Graphics/study3_1.png)


![alt text](https://github.com/ElielVSAlmeida/Crypto-Project/blob/main/Graphics/study3_2.png)
