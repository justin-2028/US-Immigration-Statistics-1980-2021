# US Immigration Statistics 1980-2021

![](https://www.googleapis.com/download/storage/v1/b/kaggle-user-content/o/inbox%2F12064410%2F468b9ab69fbaa3eea94ab7c13537052f%2Fimmigration%20flag.png?generation=1673145948097950&alt=media)

# 15,341 DAYS (October 1st, 1979 - September 30th, 2021)
This is a dataset that describes annual statistics regarding US immigration between the 1980-2021 fiscal years.

All data are **official** figures from the Department of Homeland Security's government website that have been compiled and structured by myself. There are several reasons for the decision to only examine immigration data from 1980 to 2021. Since 1976, a fiscal year for the US government has always started on October 1st and ended the following year on September 30th. If the years prior to 1976 were included, the data may be incorrectly represented and cause further confusion for viewers. Additionally, the United States only tracked refugee arrivals after the Refugee Act of 1980, a statistic that is prominently featured in the dataset. As a result, the start date of 1980 was chosen instead of 1976. 

# Data Sources
##### The primary data sources used were the "Yearbook of Immigration Statistics" webpages from the Department of Homeland Security. As a whole, the website not only provided figures about US immigration that were perfect for making time series analyses, but also explored the logistics behind the annual trends found.

1. [The Department of Homeland Security's 2021 Yearbook of Immigration Statistics](https://www.dhs.gov/immigration-statistics/yearbook/2021) - The Office of Immigration Statistics' 2021 Flow Reports and Population Estimates provide text, tables, and charts on lawful permanent residents, refugees and asylees, nonimmigrant admissions, naturalizations, enforcement actions, and the unauthorized population. Being the latest version released to date, the 2021 yearbook is the most comprehensive report publicly available and tends to feature data of past years for reference.
2. [The Department of Homeland Security's Directory of Past Immigration Yearbooks](https://www.dhs.gov/immigration-statistics/yearbook) - Past yearbooks were referenced in order to find the missing data from the fiscal years during 2000-2021. There is a single yearbook covering the fiscal years during 1996-1999, but that was the oldest publications featured in the directory.
3. [The Center for Immigration Studies's File Library](https://cis.org/) - In order to procure immigration data during the fiscal years of 1980-1999, I found free versions of the Immigration and Naturalization Service's paywalled yearbooks from the Center for Immigration Studies. By doing so, I was able fill in the missing values and finish the dataset. 

# Statistics Being Tracked
- **Immigrants Obtaining Lawful Permanent Resident Status** - Number of immigrants who obtained lawful permanent resident status in the United States, otherwise known as green card holders. 
- **Refugee Arrivals** - Number of refugees who arrived in the United States. Excludes Amerasian immigrants except for the fiscal years of 1989 and 1991. Figures are based on refugee's arrival date.
- **Noncitizen Apprehensions** - Number of noncitizens apprehended in the United States. Data from 2020 to 2021 includes U.S. Customs and Border Protection (CBP) encounters that resulted in expulsion on public health grounds (due to the pandemic).
- **Noncitizen Removals** - Number of noncitizens removed from the United States. Removals are the compulsory and confirmed movement of an inadmissible or deportable noncitizen out of the United States based on an order of removal. 
- **Noncitizen Returns** - Number of noncitizen returns from the United States. Returns are the confirmed movement of an inadmissible or deportable noncitizen out of the United States not based on an order of removal. 

# Dataset History
2023-01-07 - Dataset is created (465 days after the end of the 2021 fiscal year).

[Kaggle Dataset](https://www.kaggle.com/datasets/justin2028/us-immigration-statistics-1980-2021) - The same data but on Kaggle.

# Code Starter
[Link to Notebook](https://www.kaggle.com/code/justin2028/us-immigration-statistics-1980-2021-code-starter)
