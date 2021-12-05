# Covid-19-Report
Covid-19 has hit all of us badly. Its impressions will last forever. It has shutdown businesses, affected economies and without a question, health. We have lost a lot of near and dear ones. To analyze the effects of Covid-19, I have used Power BI. 

Power BI is a data visualization tool by Microsoft and it has free desktop version. However, to use it professionally, we need to purchase the license. There are two types of license available - pro and premium. Power BI can get data from assorted data sources like databases, flat files, excel files, sharepoint, web etc. It used a basic ETL tool - Power query.

# Import data for Power BI Report
* Launch Power BI Desktop and import data from a web data source using Get Data -> CSV -> covid-19-report.csv(File is attached).
* Select the file and click on Transform Data.

Before we prepare a visual, we need the following changes in the data set.

* Click on Use first row as a header to use table column header.
* File might contains NULL values and rows with unknown value so remove that.
* It is an important aspect the categorize each column with appropriate data types as well. If we do not assign the correct data type, it might create inaccurate charts since it does not recognize correct entries.
* Save the changes (Close & Apply), and we get the data set in Power BI as shown below.
