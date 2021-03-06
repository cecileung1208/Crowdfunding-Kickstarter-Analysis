# Crowdfunding-Kickstarter Analysis

![Image](https://cdn0.tnwcdn.com/wp-content/blogs.dir/1/files/2017/06/ksimage-796x389.jpg)

## Background

4,000 projects will be examined to determine the success strategies and key trends to secure funding from Kickstarter, a highly successful crowdfunding service donor.

## Requirements

* **Stacked Bar Graph** - Number of Campaigns' State vs. Parent-Category with Drop Down Menu to select results for each Country
* **Stacked Bar Graph** - Number of Campaigns' State vs. Sub-category with Drop Down Menus to select results for each Country and by Parent-Category.
* **Line Graph** - Number of Campaigns' State for each Month and Drop Down Menus to select results for each Year and by Parent-Category.
* **Line Graph** - % of Campaigns' State vs. Funding Goals.
* **Statistics Summary** - Backers Count for Successful and Failed Campaigns
  * Statistic calculation includes mean, median, minimum value, maximum value, variance (population & sample) and standard deviation (population & sample).
  
## Method 
<details>
 <summary><b>Campaign Details</b></summary>
 
An excel file has been provided with the details of the 4,000 projects to conduct the following analysis:
* Define the campaign status in the "state" column with conditional formatting using a 4-color scale. 
* Create a new column Percent Funded to calculate the Percent(%) Fundedd for each project and use conditional formatting using a 3-color scale.
* Create a new column Average Donation that uses a formula to uncover how much each backer for the project paid on average.
* Create two new columns, Category andSub-Category, which use formulas to split the Category and Sub-Category column into two parts.
</details>

<details>
 <summary><b>Campaign State vs. Parent-Category with Country Drop Down Feature</b></summary>
 
* Insert pivot tab in a new tab.
* Field List will be populated and drag the following:
  * state into the columns section
  * parent-category into the rows section
  * country into the filter section 
  * state values section - ensure to have the value field settings as count.
* Upon completing the pivot table, ensure it is selected and click the Pivot Chart button from the PivotAnalyze Menu.
* Choose columns and ensure it is in a bar stacked format.
* Format titles, axis as necessary.
</details>

<details>
 <summary><b>Campaign State vs. Sub-Category with Country and Parent-Category Drop Down Feature</b></summary>
 
* Insert pivot tab in another tab.
* Field List will be populated and drag the following:
  * state into the columns section
  * sub-category into the rows section
  * country field and parent-categories into the filter section 
  * state values section - ensure to have the value field settings as count.
* Upon completing the pivot table, ensure it is selected and click the Pivot Chart button from the PivotAnalyze Menu.
* Choose columns and ensure it is in a bar stacked format.
* Format titles, axis as necessary.
</details>

<details>
 <summary><b>Campaign State by Month with Year and Parent-Category Drop Down Feature</b></summary>
 
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
</details>

<details>
 <summary><b>Percent of Campaign States vs. Funding Goals</b></summary>
 
* Create a new tab with 8 columns and 12 rows.
  * Columns: Goal, Number Successful, Number Failed, Number Canceled, Total Projects, % Successful, % Failed, % Canceled
  * Rows (under Goal Column): <1000, 1000-4999, 5000-9999, 10000-14999, 15000-19999, 20000-24999, 25000-29999, 30000-34999, 35000-39999, 40000-44999, 45000-49999, >=50000
* Use COUNTIFS formula to calculate Number Sucessful, Failed and Canceled
* Sum up the the figures in Total Project
* Calculate the % of Project Status against Total Project
* Select the Goal, % Successful, % Failed and % Canceled and click on Insert tab to create Line Graph
* Format titles, axis as necessary.
</details>
 
<details>
 <summary><b>Statistics of Backers Count for Successful and Failed Campaigns</b></summary>
 
* Filter for Success Campaigns under the state column and copy and copy and paste this column and the backers count into another tab.
* Filter for Failed Campaigns under the state column and copy and paste this column and the backers count beside teh successful campaigns information.
* Create a table with Columns for Successful and Failed.
* Create rows for mean, median, minimum value, maximum value, variance (population & sample) and standard deviation (population & sample).
</details>

## Excel Analysis

Requirements of Results:
[Crowdfunding Kickstarter Analysis file](https://github.com/cecileung1208/Crowdfunding-Kickstarter-Analysis/blob/master/Crowdfunding%20Kickstarter%20Analysis.xlsx).

Limitations of Excel and Potential Tables/Graphs:
[Analysis](https://github.com/cecileung1208/Crowdfunding-Kickstarter-Analysis/blob/master/Analysis.docx)

## Results

**Campaign State vs Parent-Category** 
* Of the 4000 campaigns, over 2000 campaigns were successful, 1500 failed, 350 cancelled and 50 are live.
* Theatre, Music, and Film & Video makeup 75% of the successful campaigns.
* Theatre and Technology makeup for 45% of the failed campaign.
* Technology makeup 50% of the canceled campaigns.
* There are more failures than success campaigns for categories in food, games, photography and publishing.

![Image](https://github.com/cecileung1208/Crowdfunding-Kickstarter-Analysis/blob/master/Image/State%20vs%20Parent.png)

**Campaign State vs Sub-Category**
* Plays, rock, documentary, hardware and indie rock make up of 65% of the successful campaigns.
* Classical music, documentary, electronic music, hardware, metal, nonfiction, pop, tabletop games, rock and television have 100% success rate.
* Food trucks, translations, wearables, and web have mainly failed and cancelled campaigns.
* Animation, children's books, drama, fiction, gadgets, jazz, mobile games, nature, people, places, restaurants, and video games have 100% failure rate.
* All campaigns for world music, science fiction, art books and audio have 100% cancellation rate.

![Image](https://github.com/cecileung1208/Crowdfunding-Kickstarter-Analysis/blob/master/Image/State%20vs%20Sub-Category.png)

**Campaign State vs Month**
* There are the most successful canoaigns during April to June.  
* Successful and Failed campaigns are pretty much the same for September and December.
* Cancellation campaigns remain constant throughout the year.

![Image](https://github.com/cecileung1208/Crowdfunding-Kickstarter-Analysis/blob/master/Image/State%20vs%20Month.png)


**Campaign State vs Percentage**
* The higher the funding goals, the lower the successful rates.
* The higher the funding goals, the higher the failure rates.
* Cancellation rates gradually increase when the funding goals increase.

![Image](https://github.com/cecileung1208/Crowdfunding-Kickstarter-Analysis/blob/master/Image/State%20vs%20Percentage.png)

**Backer's Count Statistics**
* The mean is the average number of backers for the campaigns. This mean figure from the above table will determine how many backers I will usually have for the campaign if it is a success or a failure.
* The median is the middle figure of all the samples in the successful and failed campaigns.
* These figures are useful because it tells us what is normal in each situation.  For example, the organizers will know if the project is a success or failure given how many backers they receive for the project.
* It is helpful in determining one set of data against the entire set of data.  It benchmarks on how well the campaign is doing against the perceived average. 
* There is more variability with successful campaigns compared to the failed campaigns and this makes sense because  the range of value is a lot higher in the successful campaign are hence becomes more spread out from the mean.  
  * The range for the successful campaigns is 26,457 vs. 1293 for failed campaigns.

![Image](https://github.com/cecileung1208/Crowdfunding-Kickstarter-Analysis/blob/master/Image/Backers'%20Count%20Statistics.png)
