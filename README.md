# Visualizing-Euro-USD-rates

## Telling a Story about Exchange Rates with Data Visualization

This project will explore explore exchange rates at various point of time dating back to 1999 all the way up to 2021. I'll be exploring the relationships between the euro (symbolized with €) and the dollar (symbolized with $). 

Some things to highlight before we start:
* If the exchange rate of the euro the US dollar is 1.5, it means that you get 1.5 IS dollars if you pay 1.0 euro (one euro has more value than one US dollar at this exchange rate). 
* The data can be found on [Kaggle](https://www.kaggle.com/datasets/lsind18/euro-exchange-daily-rates-19992020). Daria Chemkaeva put together the data set and made it available. The data source is the European Central Bank. Note that the dataset gets regular updates — we downloaded it on January 2021.

The workflow of this project consisted of:
- Importing Packages
- Pulling in Data
- Cleaning Data
- Segmenting Data
- Visualizing the 2007-2008 Financial Crisis
- Visualizing the difference in the euro-USD rates over 3 presidencies. 

### Exploratory Data Analysis

<img width="576" alt="image" src="https://user-images.githubusercontent.com/77873198/161899974-a8f05be8-fbec-4530-82b4-514a9c86a06d.png">

### Observations
The graph above shows daily trends which makes for a lot of variation and a lot of reading. A lot of companies operate on the basis of quarters or years so we'll use a **rolling mean** to determine the moving average over time. This is the value on a day to day basis from the current daily mean and the previous days' mean. We're going to use this rolling means metric to explore deeper problems. 

### Visualizing the various types of rolling means

<img width="825" alt="image" src="https://user-images.githubusercontent.com/77873198/161900164-7cbf7294-ecd5-467e-a88d-419ea1357069.png">

### Note
 Rolling means are the mean between a current period of time and a certain amount of time elapsed. A one-day rolling mean is the mean between the present day and yesterday as an example. 


### Visualizing the 2007-2008 Financial Crisis

<img width="804" alt="image" src="https://user-images.githubusercontent.com/77873198/161900341-88909cd2-41ea-40ec-b78b-4082f0fcecdb.png">

### Observations
- The euro-usd rate peaked during the time period from 2008-2009 at a value of 1.59. 
- There was a period of recession through early 2009 with some recovery occuring later that year. However, there was another big dip in early 2010. 

### Visualizing the change of the Euro-USD relationship over 3 different presidencies. 

<img width="821" alt="image" src="https://user-images.githubusercontent.com/77873198/161900483-54574c18-921e-46e6-b4fc-f6ba6895b62d.png">


### Conclusions

- From what we can see, the most growth happened during George Bush's tenure.
- Obama's tenure started right at the start of the recession so the value of the dollar was quite volatile. 
- Trump's period saw sustained growth from the lowpoints right after Obama took office. It's tought to capture the full-scope of the situation especially when you have to consider external factors. 
