# A/B Test to Inform Business Decisions 
## [Project Summary]( https://emmanuel-nti.github.io/AB_test_to_inform_business_decisions/)

| Project Description | Libraries Used | Source of Data |
| :---------------------- | :---------------------- | :---------------------- | 
|As an analyst at a big online store. Together with the marketing department, I have compiled a list of hypotheses that may help boost revenue. I need to prioritize these hypotheses, launch an A/B test, and analyze the results.| *pandas*, *matplotlib.pyplot*, *Numpy*, *Scipy* | Practicum by Yandex |


## Description of Data

### Data used in the first part of the project

**Hypothesis dataset**
- `Hypotheses:` brief descriptions of the hypotheses
- `Reach:` user reach, on a scale of one to ten
- `Impact:` impact on users, on a scale of one to ten
- `Confidence:` confidence in the hypothesis, on a scale of one to ten
- `Effort:` the resources required to test a hypothesis, on a scale of one to ten. The higher the Effort value, the more resource-intensive the test.

### Data used in the second part of the project

**orders dataset**
- `transactionId:` order identifier
- `visitorId:` identifier of the user who placed the order
- `date:` date of the order
- `revenue:` revenue from the order
- `group:` the A/B test group that the user belongs to

**visits dataset**
- `date:` date
- `group:` A/B test group
- `visits:` the number of visits on the date specified in the A/B test group specified
