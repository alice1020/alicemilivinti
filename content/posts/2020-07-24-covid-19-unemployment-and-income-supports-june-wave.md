---
title: 'COVID-19: Unemployment and Income Supports June Wave'
author: Alice Milivinti
date: '2020-07-24'
slug: covid-19-unemployment-and-income-supports-june-wave
categories: []
tags: []
---

This is a collaboration with [Rebecca Hasdell](https://scholar.google.com/citations?user=GP4jjpIAAAAJ&hl=en) and [David Rehkopf](https://scholar.google.com/citations?user=85mEA54AAAAJ&hl=en).

The post provides an updated analysis to the post [COVID-19: Unemployment and Income Supports April Wave](https://aliceindataland.rbind.io/posts/covid-19-unemployment-and-income-supports/) by including data available until the June wave of the current Population Survey. For more details please refer to the previous post.


## Statistical Exploration
We are interested in analyzing the effects of COVID-19 on the employment status with a focus on the Earned Income Tax Credit (EITC). 

### Individual Level Longitudinal Analysis
At an individual/household level the sample size for individuals and households observed both in March 2019 (ASEC wave) and June 2020  corresponds to 10,141 individuals and 4,327 households. Among those a sub-sample of 4,797 individuals grouped in 2,947 households are part of the labor force. At the end, ~7% of the households in the sub-sample have received EITC.


|   Level    | # Obs. 03-19 & 04-20 | In the Labor Force | with EITC > 0 |
|------------|----------------------|--------------------|---------------|
| Individual |        10,141        |        4,797       |      401      |         
| Household  |         4,327        |        2,947       |      383      |

Approximately 16.4% of people who received the EITC in 2019 are experiencing unemployment between February and June 2020. This represents an increase of the 350% with respect to June 2019.

<center>
![](/img/COVID-19-EITC-June/EITC_Emp_Sub_W.png)
**Fig. 3:** EITC 2019 and Employment status in June 2020
</center>


Codes for this part are available in the file: [Disaggregated_Analysis_June.R](https://github.com/alice1020/COVID-unemployment-and-income-supports/blob/master/Disaggregated_Analysis_June.R)


### Aggregate Occupational Level Analysis

We analyze the CPS data by aggregating over the occupational categories. Our cross-sectional unit becomes the occupational category. 

### Employment vs Unemployment

We explore the impact of COVID-19 on employment. 
<center>
![](/img/COVID-19-EITC-June/Empl_Occ.png)
**Fig. 4:** % Difference in employment between February and June 2020 by occupational category.
</center>

<center>
![](/img/COVID-19-EITC-June/W_Dist_Rout.png)
**Fig. 5:** Wage Distribution by Occupation.
</center>

<center>
![](/img/COVID-19-EITC-June/Empl_Rout.png)
**Fig 6:** % Difference in employment between February and June 2020 for by wage quartile. 
</center>

###  Hours Worked

<center>
![](/img/COVID-19-EITC-June/Hrs_Occ.png)
**Fig. 7:** Difference in hours usually worked per week at the main job between February and June 2020 by occupation (unemployed with hrs = 0 are included).
</center>

<center>
![](/img/COVID-19-EITC-June/Hrs_Occ_Emp.png)
**Fig. 8:** Difference in hours usually worked per week at the main job between February and June 2020 by occupation among employed only.
</center>

### Weekly Earnings

<center>
![](/img/COVID-19-EITC-June/Earn_Occ_Emp.png)
**Fig. 9:** Difference in weekly earnings at the main job between February and June 2020 by occupation among employed only.
</center>


### EITC by Occupational Category
  
<center>
![](/img/COVID-19-EITC-June/EITC_Occ.png)
**Fig. 10:** Average EITC perceived in 2019 vs % Difference in employment between February and June 2020 by occupational category.
</center>

Codes for this part are available in the file: [Aggregated_Analysis_June.R](https://github.com/alice1020/COVID-unemployment-and-income-supports/blob/master/Aggregated_Analysis_June.R)


  



