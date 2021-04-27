# An Analysis on Kickstarter Campaign

## Introduction
Louis wants to do a Crowd funding Campaign to fund her play "Fever", with an estimated budget of $10000+ for Sets, Costumes, Props, Makeup, Lighting,Rehearsal Space, Advertising, Programs and actors. Here is  Analysis on crowd funding data from US and Great Britain for Theater/Plays to determine weather there are specific projects that make project campaign succesful. This data analysis should help Louis to uncover trends and plan her own Campaign to fund her play "Fever".

## Preliminary Analysis
Analysis started with a dataset of ~4,000 projects, and created additional features to include, "Percent Funded" and "Average Donation". The "Category and Sub-Category" feature was also divided into two, separate columns labeled, "Category" and "Sub-Category", to more accurately define the results in later analyses. Next, we conducted exploratory data analysis to quickly identify any trends by color coding the outcome and percentage funded categories.

## Data Analysis
First, we examined the relationship between the project category and its outcome to determine which category had the highest success rate. As shown in "US Parent Category Stats", the category that had the highest success rate was Music (77%), followed by Theater (~62%), and Film & Video (58%) respectively.

### US Parent Category Stats![image](https://user-images.githubusercontent.com/82982480/115709736-3012cf80-a337-11eb-87cd-e57cbddc1e27.png)

The next relationship we analyzed was based on the time of year (month) in which the project was conducted and the subsequent outcomes. line graph "Theater_Outcomes_vs_Launch" shows that projects conducted in the first half of the year are significantly more likely to succeed than those conducted in the latter half. Note, the month of May had the highest number of successful outcomes where December had the least.

### Theater_Outcomes_vs_Launch![image](https://user-images.githubusercontent.com/82982480/116178839-d5cd9200-a6db-11eb-9f20-d55cb7189609.png)

Finally, we examined the different outcomes based on the project's goals. The line chart "Outcomes_vs_Goals" seems to indicate that, the lower goal, the more likely it is to succeed. It is important to note that, of the goals that are 14,999 or higher, there seems to be very low success rate!

### Outcomes_vs_Goals![image](https://user-images.githubusercontent.com/82982480/116179347-cc90f500-a6dc-11eb-8ba8-ec67e36e6b27.png)

## Conclusions
Based on the data analyzed, there is a fair chance of successful outcome based on the project's category, sub-category and timing. As we are helping out Louis on the plays, we did analyze Theater category at ~62% success rate and sub-category Play at ~67% success rate. The results show that May is the best month to conduct a campaign. The final analysis show that plays with smaller goals (less than 5000) are the most successful. 90% of the plays analyzed were under $15,000 and had good success rate. Plays with goals greater than 15,000 are the least likely to succeed. 
 ### Limitations
 1. The dataset used only represented about 1% of the total number of Kickstarter campaigns conducted, and may not accurately represent the data of all Kickstarter campaigns.
 2. Scope limitations – The scope of our assignment was only to evaluate three conclusions based on the data. There may be other factors that influence the success of a campaign that were not analyzed. For example, the duration of the campaign, geographical considerations, whether or not the campaign was "staff picked", and average donation are all additional analyses that could be conducted to make additional conclusions.
 3. Lack of information about the Backers restricted our ability to conduct further analysis as to which types of Backers are most associated with successful campaigns.
 ### Future Work
As we mentioned earlier, there are several other factors of interest that could be analyzed. More specifically, a report including the likelihood of conducting a successful campaign based on:
  * The duration of the project
  * Geography – by country, by state (USA)
  * Whether or not the campaign was designated as a "staff pick"
  * Backer information – number of backers, demographic data, social network, etc.
  * Average Donation
would yield a more comprehensive analysis with increased confidence in the accuracy of its findings.
