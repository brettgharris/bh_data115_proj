# Marriage Rates in the US

## MOTIVATION:
Marriage rates have been dropping over the past 20+ years due to a number of sociological factors. I set out to analyze marriage rates within the US and how select states from  different regions and demographics of the US differ and relate to the national average from 2000-2019. The states and reasons for which I have chosen them are as follows: Nevada (gnerally looser laws than the rest of the nation, Southwest), Washington (Pacific Northwest), Indiana (Midwest), Mississippi (South), Connecticut (Northeast)
  
## DATA PROCESS:
My data came from the United States Center for Disease Control (https://www.cdc.gov/nchs/nvss/marriage-divorce.htm?CDC_AA_refVal=https%3A%2F%2Fwww.cdc.gov%2Fnchs%2Fmardiv.htm). The two files of data I used are located under the "Detailed State Tables" section of the link. My first step was to reformat the data in such a way that it would be translatable in R for analyses. The data did not have to be cleaned, the CDC did a great job at providing the data completely and correctly (except for select states that did not disclose their demographic data). I then used RStudio to create scatter plots for the data with Locally Weighted Scatterplot Smoothing (LOWESS) lines to easily understand the visualizations (seen below). 

## VISUALIZATION:
![image](https://github.com/brettgharris/bh_data115_proj/blob/main/marriage_rate_plots.png)
This figure shows 6 scatter plots with LOWESS lines. The national marriage rate is in the top left corner with the 5 selected states following. I wanted to have all the plots together to easily show the difference in each of their respective marriage rates. LOWESS allows for a linear and nonlinear form of regression to be present in the data. The smooth weighted lines help to clearly display the marriage rates of the states and nation from 2000-2019.

  
## ANALYSIS:
I used LOWESS for my analysis. LOWESS allowed for me to analyze the marriage rates without sticking to just linear regression. I believe linear regression alone would not have worked here because the time frame is over 20 years and I wanted to show just exactly how these marriage rates were changing together throughout the years. When analyzing the data we see that the national marriage rate decreased from 2000-2010, but then started to level out. Similarly, the 5 states also had decreasing marriage rates from 2000-2010. Nevada had the largest decrease from about 72 marriages per 1,000 people to 38. Connecticut decreased the least, from 5.7 to 5.6. Mississippi stood alone in having an increasing marriage rate after 2010, as opposed to the national rate, bringing their average back to around the same place it was in 2000. 
