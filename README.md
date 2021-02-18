# Crowdfunding-Kickstarter Analysis

![Image](https://cdn0.tnwcdn.com/wp-content/blogs.dir/1/files/2017/06/ksimage-796x389.jpg)

## Background

4,000 projects will be examined to determine the success strategies and key trends to scure funding from Kickstarter, a highly successful crowdfunding service donor.

## Requirements

* Create a stacked bar graph displaying the number of campaigns' state vs. parent-category with a dropdown menu to see the results by country.
* Create a stacked bar graph displaying the number of campaigns' state vs. sub-category with a dropdown menu to see the results by country and parent-category.
* Create a line graph displaying the number of campaigns' state for each month with a dropdown menu to see the results by years and parent-category.
* Calculate number and % of the campaigns' state against the funding goals.
* Create a statistical summary for the backers count in successful and failed campaings.
  * Statistic calculation includes mean, median, minimum value, maximum value, variance (population & sample) and standard deviation (population & sample).
  
## Method 

**Worksheet**
An excel file has been provided with the details of the 4,000 projects to conduct the following analysis:
* Define the campaign status in the "state" column with conditional formatting using a 4-color scale. 
* Create a new column Percent Funded to calculate the Percent(%) Fundedd for each project and use conditional formatting using a 3-color scale.
* Create a new column Average Donation that uses a formula to uncover how much each backer for the project paid on average.
* Create two new columns, Category andSub-Category, which use formulas to split the Category and Sub-Category column into two parts.

**Stacked Bar Graph - Number of campaigns vs. parent-category with drop down menu for each country**
* Insert pivot tab in another tab.
* Field List will be populated and drag the following:
  * state into the columns section
  * parent-category into the rows section
  * country into the filter section 
  * state values section - ensure to have the value field settings as count.
* Upon completing the pivot table, ensure it is selected and click the Pivot Chart button from the PivotAnalyze Menu.
* Choose columns and ensure it is in a bar stacked format.
* Format titles, axis as necessary.

**Stacked Bar Graph - Number of campaigns vs. sub-category with drop down menu for each country and parent-category**
* Insert pivot tab in another tab.
* Field List will be populated and drag the following:
  * state into the columns section
  * sub-category into the rows section
  * country field and parent-categories into the filter section 
  * state values section - ensure to have the value field settings as count.
* Upon completing the pivot table, ensure it is selected and click the Pivot Chart button from the PivotAnalyze Menu.
* Choose columns and ensure it is in a bar stacked format.
* Format titles, axis as necessary.

**Line Graph - Campaign State for each month with drop down menu for years and parent-category**
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


## Excel Analysis

## Results
