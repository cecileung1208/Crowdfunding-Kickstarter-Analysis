# Crowdfunding-Kickstarter Analysis

![Image](https://cdn0.tnwcdn.com/wp-content/blogs.dir/1/files/2017/06/ksimage-796x389.jpg)

## Background

4,000 projects will be examined to determine the success strategies and key trends to scure funding from Kickstarter, a highly successful crowdfunding service donor.

## Requirements

* **Stacked Bar Graph** - Number of Campaign's State vss Parent-Category with Drop Down Menu to select results for each Country
* **Stacked Bar Graph** - Number of Campaigns' State vs. Sub-category with Drop Down Menus to select results for each Country and by Parent-Category.
* **Line Graph** - Number of Campaigns' State for each Month and Drop Down Menus to select results for each Year and by Parent-Category.
* **Line Graph** - % of Campaigns' State vs. Funding Goals.
* **Statistics Summary** - Backers Count for Successful and Failed Campaigns
  * Statistic calculation includes mean, median, minimum value, maximum value, variance (population & sample) and standard deviation (population & sample).
  
## Method 

**Worksheet**
An excel file has been provided with the details of the 4,000 projects to conduct the following analysis:
* Define the campaign status in the "state" column with conditional formatting using a 4-color scale. 
* Create a new column Percent Funded to calculate the Percent(%) Fundedd for each project and use conditional formatting using a 3-color scale.
* Create a new column Average Donation that uses a formula to uncover how much each backer for the project paid on average.
* Create two new columns, Category andSub-Category, which use formulas to split the Category and Sub-Category column into two parts.

**Stacked Bar Graph** - Number of Campaign's State vss Parent-Category with Drop Down Menu to select results for each Country
* Insert pivot tab in another tab.
* Field List will be populated and drag the following:
  * state into the columns section
  * parent-category into the rows section
  * country into the filter section 
  * state values section - ensure to have the value field settings as count.
* Upon completing the pivot table, ensure it is selected and click the Pivot Chart button from the PivotAnalyze Menu.
* Choose columns and ensure it is in a bar stacked format.
* Format titles, axis as necessary.

**Stacked Bar Graph** - Number of Campaigns' State vs. Sub-category with Drop Down Menus to select results for each Country and by Parent-Category.
* Insert pivot tab in another tab.
* Field List will be populated and drag the following:
  * state into the columns section
  * sub-category into the rows section
  * country field and parent-categories into the filter section 
  * state values section - ensure to have the value field settings as count.
* Upon completing the pivot table, ensure it is selected and click the Pivot Chart button from the PivotAnalyze Menu.
* Choose columns and ensure it is in a bar stacked format.
* Format titles, axis as necessary.

**Line Graph** - Number of Campaigns' State for each Month and Drop Down Menus to select results for each Year and by Parent-Category.
* In the worksheet, create 2 columns date created conversion and date end conversion to [format the date](https://www.extendoffice.com/documents/excel/2473-excel-timestamp-to-date.html) from the launched_at and deadline columns respectively.
* Insert pivot tab in another tab.
* Field List will be populated and drag the following:
  * state field into the columns section
  * date created conversion into the rows section
  * years and parent-categories into the filter section 
  * state field into the values section - ensure to have the value field settings as count.
* Upon completing the pivot table, ensure it is selected and click the Pivot Chart button from the PivotAnalyze Menu.
* Choose lines and create graph.
* Format titles, axis as necessary.

**Line Graph** - % of Campaigns' State vs. Funding Goals
* Create a new tab with 8 columns and 12 rows.
  * Columns: Goal, Number Successful, Number Failed, Number Canceled, Total Projects, % Successful, % Failed, % Canceled
  * Rows (under Goal Column): <1000, 1000-4999, 5000-9999, 10000-14999, 15000-19999, 20000-24999, 25000-29999, 30000-34999, 35000-39999, 40000-44999, 45000-49999, >=50000
* Use COUNTIFS formula to calculate Number Sucessful, Failed and Canceled
* Sum up the the figures in Total Project
* Calculate the % of Project Status against Total Project
* Select the Goal, % Successful, % Failed and % Canceled and click on Insert tab to create Line Graph
* Format titles, axis as necessary.
 
**Statistics Summary** - Backers Count for Successful and Failed Campaigns
* Filter for Success Campaigns under the state column and copy and copy and paste this column and the backers count into another tab.
* Filter for Failed Campaigns under the state column and copy and paste this column and the backers count beside teh successful campaigns information.
* 

## Excel Analysis

## Results
