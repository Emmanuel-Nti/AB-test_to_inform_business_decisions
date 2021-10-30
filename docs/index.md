# A/B Test to Inform Business Decisions
<p align ="center">
   <img src = "images/ab.png" width="1000" 
     height="500">
 </p>
## [Detailed Project Link](https://nbviewer.org/github/Emmanuel-Nti/AB-test_to_inform_business_decisions/blob/master/AB_testing_Nti.ipynb)

## How I Approached the Project
- Importation of the data and libraries
- Preprocessed the data 
- Prioritized Hypotheses
  - Applied the ICE and RICE framework to prioritize hypotheses
-  A/B Test Analysis
- Conclusion 
 
## General Findings
- A total of 181 visitors belong to both group A and B; I droped them.
- Out of 9 hypotheses, hypotheses 8, 0, and 7 had the highest ICE score ( all three have at least a score of 11), the least score is hypothesis 4
- Hypotheses 7,2, 0, and 6 have the highest RICE score (all four have at least a score of 40), the least score is hypothesis 4.
- Group B led in revenue in most part of the test and the gap increased after August 17, 2019. The spike implied either a surge in the number of orders or the presence of very expensive orders in the sample; a hint of outliers in the data.
- At the begining of the test, the conversion rate of group A was higher. After few days, group B took over and lead till the end of the test. 
- Based on raw data, there is significant difference in conversion rate between groups A and B. 
- Based on filtered data, there is significant difference in conversion rate between groups A and B. Hence, the test was successful.

## Recommendations
- Stop the test, consider group B as the leader.
- Although there is no signficant difference between the groups considering their average order size, there is statistically and significant difference in conversion between the groups, and group B's relative conversion gain is significant.

## Libraries Used
- Pandas 
- Numpy 
- Matplotlib
- Scipy  

