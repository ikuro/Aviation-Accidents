# Aviation-Accidents

Analysis on the Aviation dataset
# Business Goal

## Understanding Aviation risks:

Identify key factors that influence flight accidents, such as year, instrument use,location engines, purpose…

## Identifying Trends:

Explore patterns in accidents across various countries, period…

# Data Understanding
The dataset dataset provides a detailed and comprehensive collection of aviation dataset which will help us determine which aircraft are the lowest risk for the company to start in this new aviation business. 
It encompases a wide range of information and from this, the stakeholder is interested to uncover trends and insights regarding aviation accidents in the USA and in international waters from 1962 to 2023.

### Loading The Data

---
### Data Cleaning/preparation
1. Checking the data structure, shape
2. Drop columns that had missing values >30%
3. Check for duplication

### Exploratory Data Analysis
- Quick Descriptive analysis of both categorical and numerical variables
- Visualize specific variables of importance to the exercise and check for relationship
-Engineer some columns

### Further Data Cleaning/preparation
- Replace missing based on context. 
- Create additional columns
- Further descriptive analysis to asess progress
### Data Analysis
Include some interesting codes
``` Main notebook. Refer to Aviation Analysis.ipynb ;
```
### Results/findings
The analysis results are summarized as follows:
#### Link to Tableau
[Tableau Dashboard](https://public.tableau.com/app/profile/george3771/viz/AviationData_17323494014070/Dashboard1?publish=yes/)


<img width="473" alt="BI2" src="https://github.com/ikuro/Aviation-Accidents/blob/main/Dashboard.PNG">

- or quick view from python

<img width="473" alt="BI2" src="https://github.com/ikuro/Aviation-Accidents/blob/main/Scatter1.png">

<img width="473" alt="BI2" src="https://github.com/ikuro/Aviation-Accidents/blob/main/barplot2.png">

<img width="473" alt="BI2" src="https://github.com/ikuro/Aviation-Accidents/blob/main/barplot3.png">

<img width="473" alt="BI2" src="https://github.com/ikuro/Aviation-Accidents/blob/main/linegraph2.png">

### Recommendations
Based on the analysis, we recommend the following actions:
1. The decrease in aviation accidents since since after 1981 is encouraging, but there are countries that one needs to deploy more measures to safeguard life and business. In high-accident states, there should be a concerted effort to increase surveillance and regulatory enforcement activities to mitigate the risks associated with aviation accidents.

2. Based on the fact that we had a high visual determining of weather, it is an indication that many accidents happened on a good weather, provoking pilots to use their eyes/visual for decision making. It is imperative to  reinforce guidance and adherence to protocals  when in the sky unless it is unavoidable.

3. The purpose came out as a big contributing factor in the number of accidents. Looking at the business model our stakeholder is interested in, business/commercial purpose seem to be in line with decreased accidents. 

4. At of the look of things, increased number of engines is a guarantee in eradication of accidents. While it would have a potential implication on the cost as well, this can better concluded when cost is in play

### Limitations
- Data was fictious and we lacked substantive data beefore 1981.
- Time Factor. I could have done more

### References
1. Learning Python 5th Edition –O’Reilly
2. Youtube tutorials - [Dataschool](https://www.youtube.com/@dataschool)
3. Class work


