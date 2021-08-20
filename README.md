# An Analysis of Kickstarter Campaign Dataset

## Overview of the Project
The purpose of this project is to help Louise with a fundraising campaign for her play *Fever*. The idea is to determine how various fund raising campaign for a play in the past fared in relation to the canpaign launch dates and funding goals. This would give Louise some insight into what goals to set for her play and how the length of the campaign would correlate with her success.

## Analysis and Challenges
The analysis was carried out using the [kickstarter](/Kickstarter_Challenge.xlxs) data that contains a list of past campaign goal and pledged amounts, campaign outcomes, campaign categories, and their launch date, in a tabular form.

The analysis focussed on campaign outcomes (successful, failed, and canceled), campaign goal amount, campaign category (theater), campaign subcategory (plays), and the campaign launch date from the dataset. It resulted in two sets of analysis, 1) the outcome of the campagn in theater category based on their launch date, and 2) the outcome of campaign in a play subcategory based on goal amount.

#### Analysis of Outcomes in Theater Category Based on Launch Date
The data was analyzed by first splitting the *Category & Subcategory* column into separate *Parent Category* and *Subcategory* columns in the data sheet. The deadline and the launch date colums were converted from the Unix timestamps to a more readable format into separate columns (*Date Created Conversion* and *Date Ended Conversion* columns). A column for the year (*Years* column) was also added and extracted from *Date Created Conversion* column. 

A pivot table was generated by counting the number of outcomes (successful, failed, and canceled) for all months of the year and with filters on "Parent Category" and "Years". The "Parent Category" was filtered on "theater" and the campaign outcomes sorted in descending order. A line chart was then generated showing the number of successful, failed, or canceled projects by month. The line chart is as shown below.

![Figure 1](/resources/Theater_Outcomes_vs_Launch.png)

From the chart it is observed that the theater campaigns that were launched in the month of May was the most succesful, and those launched in the month of December were the least successful. The number of campaigns that failed were on an averge pretty steady over the period of year. There were also few campaigns that were canceled.


#### Analysis of Outcomes in Play Subcategory Based on Goals
The data for this part of the analysis was obtaned by counting the number of play subcategory with goal amount binned into smaller ranges ($1000 -$5000, $5000 -$10000,...) for variou outcomes (successful, failed, and canceled). A line chart was then generated showing the number of successful, failed, or canceled plays in percentage for various goal amount. The line chart is as shown below.

<p align="center">
![Figure 2](/resources/Outcomes_vs_Goals.png)
</p>   

The funding for the play category shows 73 - 76% success rate for funding of less than $5000. It also shows a success rate of 67% for fundings between $35000 - $45000. The succes rate was the lowest for funds above $45000 (less than 13%).

#### Challenges and Difficulties Encountered

## Results

- Louise's campaign for her play (which belong to theater category) is likely to be more successful if launched in the second or third quarter of the year.
   The campaign is likely to be successful if launced in the fourth quarter of the year.
   
- Louise's campaign with a goal amount less than $5000 is more likely to be successful. Although the data shows that some play with a funding between $35000 - $45000 may also be     successful. However, her campaign with goal amount above $45000 are most likely to fail. 

- The data probably has some outliers that needs to be sorted out and taken care of.   
 
- A box plot showing the summary statistics and possible ouliers in the data would provide further insight.
