# Marriage Rates in the US

## MOTIVATION:
Marriage rates have been dropping over the past 20 years due to a number of sociological factors. I set out to analyze marriage rates within the US and how select states from  different regions and demographics of the US differ and relate to the national average. The states and reasons for which I have chosen them are as follows: Nevada (gnerally looser laws than the rest of the nation, Southwest), Washington (Pacific Northwest), Indiana (Midwest), Mississippi (South), Connecticut (Northeast)
  
## DATA PROCESS:
My data came from the United States Center for Disease Control (https://www.cdc.gov/nchs/nvss/marriage-divorce.htm?CDC_AA_refVal=https%3A%2F%2Fwww.cdc.gov%2Fnchs%2Fmardiv.htm). The two files of data I used are located under the "Detailed State Tables" section of the link. My first step was to reformat the data in such a way that it would be translatable in R for analyses. The data did not have to be cleaned, the CDC did a great job at providing the data completely and correctly (except for select states that did not disclose their demographic data). I then used RStudio to create scatter plots for the data with Locally Weighted Scatterplot Smoothing (LOWESS) lines to easily understand the visualizations (seen below). 

## VISUALIZATION:
[text](docs/marriage_rate_plot.png)
  
## ANALYSIS:

