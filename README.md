# An Analysis of Kickstarter Campaign Dataset

## Overview of the Project
The purpose of this project is to determine how various fund raising campaign fared in relation to their launch dates and funding goals. The analysis was performed using the [kickstarter](/Kickstarter_Challenge.xlxs) dataset, which contains a list of goal and pledged amounts, outcomes, categories, and launch date, for each campaign in a tabulated form. In particular, the analysis was performed to determine the outcome of the campagn in theater category based on their launch date, and the outcome of campaign in a play subcategory based on goal amount.



## Analysis and Challenges
### Take an initial look at the data to get a sense of the data.
organize the data by using filters and formatting to generate insights for Louise's project.
use conditional formatting to customize our worksheet. This will refine the visual presentation of the data in the worksheet to provide Louise with information at a glance.
Louise is looking forward to your analysis, but she would benefit from additional visualization of the data so that she can see the outcomes of all the categories. Let's help Louise by creating summary tables, charts, and graphs.
created subcategories & parent categories
Another valuable piece of data is the length of fundraising campaigns. Is the length of a campaign correlated with its success? To help Louise plan her campaign timeline, let's take a closer look at how campaign length might be tied to its outcome. In order to do this, we'll need to convert the Unix timestamps to a more readable format.
pivot table & pivot chart

Another valuable piece of data is the length of fundraising campaigns. Is the length of a campaign correlated with its success? To help Louise plan her campaign timeline, let's take a closer look at how campaign length might be tied to its outcome. In order to do this, we'll need to convert the Unix timestamps to a more readable format.

### Analysis of Outcomes Based on Launch Date
It is observed that the theater campaigns that were launched in the month of May was the most succesful, and those launched in the month of December were least successful. The number of campaign that failed were on and averge pretty steady over the period of year. There were very few campaign that were canceled in this category.

![Figure 1](/resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
The funding for the play category shows 73 - 76% success rate for funding of less than $5000. It also shows a success rate of 67% for fundings between $35000 - $45000. The succes rate was the lowest for funds above $45000 (less than 13%).

![Figure 2](/resources/Outcomes_vs_Goals.png)
### Challenges and Difficulties Encountered

## Results

- The funding for the theater category is most likely to be more successful if launched in the second or third quarter of the year.
   The funding for the theater category is least likely to be successful if launced in the fourth quarter of the year.
   
- The play subcategory campaign with goal amount less than $5000 is more likely to be successful. Although the data shows that some play with a funding between $35000 - $45000 may be somewhat successful. But, those campaign with goal amount above $45000 are most lokely to fail. 


- What are some limitations of this dataset?
   The data probably has some outliers that needs to be sorted out and taken care of.   

- What are some other possible tables and/or graphs that we could create?
