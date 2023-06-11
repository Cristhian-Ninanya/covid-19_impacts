# **Covid-19 Impacts Analysis**

![alt text](https://github.com/Cristhian-Ninanya/covid-19_impacts/blob/main/Images/covid_cover.jpg?raw=true)

**Overview:**

The Covid-19 outbreak led to widespread restrictions, causing significant economic impacts globally, with nearly all countries being negatively affected by the surge in cases.

**Target:**

Analyze the spread of Covid-19 cases and its impact on the economy.

**DataSet information:**

The dataset we are using to analyze the impacts of covid-19 is downloaded from Kaggle (https://www.kaggle.com/datasets/shashwatwork/impact-of-covid19-pandemic-on-the-global-economy).

Dataset for GDP per capita (current US$) is downloaded from The world Bank (https://data.worldbank.org/indicator/NY.GDP.PCAP.CD?end=2021&start=2018)


**Attribute Information:**

* **iso_code(CODE)**: Country code.
* **location(COUNTRY)**: Name of all the countries.
* **date(DATE)**: Date of record.
* **total_cases(TC)**: Daily covid-19 cases.
* **total_deaths(TD)**: Daily deaths due to covid-19.
* **stringency_index(STI)**: Stringency index of the countries.
* **human_development_index(HDI)**: Human development index of all countries.
* **population**: The population of the countries.
* **gdp_per_capita**: GDP (Gross domestic product) per capita of the countries.

## Imported DataSet:

**top-10 countries by Total cases**

```
   Country Code         Country       HDI  Total Cases  Total Deaths   
0          USA   United States  0.924000  746014098.0    26477574.0  \
1          BRA          Brazil  0.759000  425704517.0    14340567.0   
2          IND           India  0.640000  407771615.0     7247327.0   
3          RUS          Russia  0.816000  132888951.0     2131571.0   
4          PER            Peru  0.599490   74882695.0     3020038.0   
5          MEX          Mexico  0.774000   74347548.0     7295850.0   
6          ESP           Spain  0.887969   73717676.0     5510624.0   
7          ZAF    South Africa  0.608653   63027659.0     1357682.0   
8          COL        Colombia  0.581847   60543682.0     1936134.0   
9          GBR  United Kingdom  0.922000   59475032.0     7249573.0   

   Stringency Index  Population  GDP Before Covid  GDP During Covid  
0          3.350949   19.617637      65120.394663      63530.633484  
1          3.136028   19.174732       8845.259118       6794.489159  
2          3.610552   21.045353       2047.232704       1910.421473  
3          3.380088   18.798668      11536.250977      10169.086914  
4          3.430126   17.311165       6955.809959       6056.343903  
5          3.019289   18.674802      10145.170183       8655.000682  
6          3.393922   17.660427      29581.518551      26959.675437  
7          3.364333   17.898266       6688.787271       5741.643129  
8          3.357923   17.745037       6438.060183       5307.215228  
9          3.353883   18.033340      42747.080460      40318.557566  
```

## Spread of covid-19:

**Countries with Highest Covid-19 Cases:**

![alt text](https://github.com/Cristhian-Ninanya/covid-19_impacts/blob/main/Images/high_cases.png?raw=true)

**OBS**:
* Based on the graph, **The United States**, **Brazil**, and **India** have the highest total COVID-19 case counts.

**Countries with the highest number of COVID-19 deaths**

![alt text](https://github.com/Cristhian-Ninanya/covid-19_impacts/blob/main/Images/high_deaths.png?raw=true)

**OBS**:
* Based on the graph, **The United States** and **Brazil** have the highest total COVID-19 deaths counts. Followed by **Mexico**, **India** and **The United Kingdom**.


**Stringency Index**

![alt text](https://github.com/Cristhian-Ninanya/covid-19_impacts/blob/main/Images/si_index.png?raw=true)

**OBS:**
* Based on the chart, **India** demonstrates a high level of adherence to COVID-19 control measures.
* **Brazil** and **Mexico** exhibit a low level of adherence to control measures for COVID-19.


## Covid-19 Impacts on Economy:

**GDP per capita**

![alt text](https://github.com/Cristhian-Ninanya/covid-19_impacts/blob/main/Images/gdp_compare.png?raw=true)

**OBS:**
* As expected, there has been a decline in the GDP per capita across all countries.

**Human Development Index**

![alt text](https://github.com/Cristhian-Ninanya/covid-19_impacts/blob/main/Images/hdi_index.png?raw=true)

**OBS:**
* During COVID-19, **The United States**, **The United Kingdom**, and **Spain** allocated the highest budget for human development spending.
* **South Africa**, **Colombia**, and **Peru** allocated the lowest budget for human development spending during COVID-19.


**Final Observations:**

From Top-10 countries by COVID-19 Total cases:

* The United States, Brazil, and India had the highest number of COVID-19 cases and deaths among the top 10 countries.

* India demonstrated a high level of compliance with COVID-19 control measures, while Brazil and Mexico exhibited a low level of adherence.

* All countries experienced a decline in GDP per capita during the COVID-19 outbreak.

* The United States, the United Kingdom, and Spain allocated the highest budgets for human development spending, while South Africa, Colombia, and Peru showed a lower level of human development index.


