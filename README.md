# Kickstarting with Excel

## Overview of Project

### Purpose

   Our customer, Louise, has requested further data analysis from our team to help her understand how different kickstarter campaigns for theater programs have fared with respect to their launch timing.  We also wanted to look at the outcomes (success, failure, cancellation) based on the size of goals set for her specific domain (theatrical plays).  Utilizing some excel formulas, pivot tables, and charts/graphs that are fitting for each aspect, we have put together the following analysis for her.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

    To help Louise get a clear picture of her interest, we created a pivot table that uses the monthly breakdown of time as the main set of rows and then compares them across the counts of differening input values from the outcome column.  We filtered this by parent category to show us only Theater campaigns.  This allows us to show line graphs for each outcome across the year as follows:

![Theater Results Across the Year](resource/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals

    For our goal comparison, we created our own sheet of formulaically-summoned information, grouped by condition from our data set, and then calculated for totals and averages.  This allows for a line graph showing the change in success as the goal levels move higher and higher through various intervals of goal levels.  It's results show a noticabel pattern as follows:

![Setting Successful Goals](resource/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered

    * One important challenge to this quick response is that the launch date graph compiles all years into one outlook by month.  It doesn't show the dramatic differences between the flow and results of each distinct year.  

    * A challege I experienced in doing the actual work was with the labor it took to duplicate/modify the conditional formatting required for counting up the number of each type of outcome for various goal levels.  Even with my best use of shortcuts, it required a number of cell-by-cell edits.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

     * Overall, this graph shows a trend of theater campaigns with a spike in success in May and June, with a downward trend hitting its lowest as the year concludes in December.
     * Theater campaigns seem to keep a pretty low number of cancelations no matter what time of the year, especially compared to other categories where canceling the campaign is far more common.

- What can you conclude about the Outcomes based on Goals?

     * Goals under ten thousand dollars, especially between 5 and 10 thousand, have a good chance of succeeding.  Above that is risky, with high failure rates spiking in the 25,000 range, and especially high after 40,000 or higher.

- What are some limitations of this dataset?
    
    One big limitation in this data is that it doesn't necessarily show the kinds of variable that are most pertinent to campaign success, such as the marketting/sharing of the campaign, the attractiveness of the cause, the compelling profile, etc.

- What are some other possible tables and/or graphs that we could create?
  
    It could be useful to look more at the donor behavior such as average donation to various types of campaigns.  Additionally, it would be worthwhile to wrangle over the kickstarter feature information like staff picks and spotlighting to see what kind of benefit might come from those elements as well.
