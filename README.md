# Time Series Analysis of Chicago Crime
___
## Analysis of Chicago crime trends, Nature and effects as a training tool in data analysis
___
- Author: `Luke Kivumbi`
### Business problem:
This dataset looks at the types of crime that were committed in Chicago over centuries. It looks at the time, location, type of crime, police district where the crime was committed. Our stakeholders have tasked us with the role of analyzing this data to under the following
1. Crimes Across the Years
   - Is the total number of crimes increasing or decreasing across the years?
   - Are there any individual crimes that are doing the opposite (e.g., decreasing when overall crime is increasing or vice-versa)?
2. Comparing Months:
   - What months have the most crime? What months have the least?
   - Are there any individual crimes that do not follow this pattern? If so, which crimes?
3. What cycles (seasonality) can you find in this data?
## Methods
___
This was a long form dataset that had to first be cleaned to get the correct datetime format for analysis. Given that this is a timeseries the index was set as the datetime column. The original row of the dataset showed a crime. the data was then transformed for each row to represent a time period; day, and this was done by moving our type of crimes to the columns and creating a new dataframe of sorts. The top crimes committed in Chicago over the years were sliced from our index and analysed for any seasonal variations and cycles over the years
The different months in a year were then analysed for crimes committed during each month and the month with the most crimes was identified. plots were made of the crimes over different months and the series was decomposed to identify the seasonal trends.
The crimes committed in different police districts were also analysed and the most affected district identified.
## Results
___
- Here are examples of some of the plots from the analysis
  
  ![series2](https://github.com/lkivumbi/Project-3/assets/161327455/7e9de906-b015-4dde-8eb5-08c63c5a5c1e)
![series1](https://github.com/lkivumbi/Project-3/assets/161327455/e0be47ef-1fce-4dd2-a0f7-4d093054b54a)
![months](https://github.com/lkivumbi/Project-3/assets/161327455/bf08d007-57ca-4f45-a11a-5d49d917c9dd)

