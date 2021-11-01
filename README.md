# Kickstarting with Excel

## Overview of Project

### Purpose
The purpose of the executed analysis was to determine, using historical data from thousands of other kickstarter projects, if Louise's Kickstarter play idea would likely receive adequate funding. Louise believes she would need to set a goal of $12,000 for her Kickstarter play *Fever*. The analysis took place not only looking at plays specifically, but also used the main category “theater” in hopes to discover additional trends.
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/92493572/139604848-c1e9b854-c85d-40df-aeaa-7a668b2370a3.png)

[Figure 1]

The first analysis looked at how Kickstarters, related to the parent category "theater", performed based on the month they were launched in. Taking a quick glance at Figure 1 it is easy to determine that plays, across the board, are more often successful than not. The number of successful Kickstarters in the theater category occurred the month of May (with a value of 111). Both sides of this point have noticeably steady declines that sink toward the months of December and January. From May to August, the successful Kickstarters become less frequent, yet the number of unsuccessful ones remains relatively flat. Because of this, it is also important to consider the percentage of successful kickstarts, and not only the number successful ones. Kickstarters for theater in May had a 66.87% success rate while June had a 65.36% success rate. According to this chart, it would be best to launch Louise's Kickstarter in the month of May, with June as the next best option.
### Analysis of Outcomes Based on Goals
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/92493572/139605011-da78ff10-346e-41b7-9be8-3d0b70382766.png)

[Figure 2]

The next analysis specifically looked at the subcategory "plays", which is what Louise plans to create. As seen in Figure 2, successful Kickstarters seem to thrive when their goals are set lower: goals of less than $1,000 saw a 75.81% success rate and goals of $1,000-$4,999 saw a 72.66% success rate between 720 plays total. Louise expects she will need to gather $12,000, so her play fits into the $10,000-$14,999 category range, which saw a 54.17% success rate (using 72 data points). After the $10,000-$14,999 range, the number of projects per category drops significantly, greatly reducing the confidence that the percentages in the chart display. After that, the success rate drops rapidly to the 50% range. In the $35,000-$44,999 range, the percent of success spikes to 66.67%, though it is worth noting that there were only 9 plays within those two goal ranges.
### Challenges and Difficulties Encountered

## Results
Based on the data provided and the analysis performed on theater outcomes based on launch date, Louise would have the best chance of success if she launched her Kickstarter in the month of May (66.87% historic success rate for theater category). Her next best option is to launch in June (65.36% historic success rate for theater category). October through have consistently lower success rates than the summer months. The only month to have under a 50% success rate was December (49.33%).

The analysis on outcomes based on goals was more specific to what Louise wants to create: a play. Based on where her play's budget sits, she would only have a 54.17% chance of success. This does not account for what month she would launch it, let alone what months other plays within her category launched theirs. As her play's category is the last with a decent sample size, also taking note of the inverse relationship between goal amount and success, she would likely benefit from reducing her budget to under $5,000, if possible. Otherwise, Louise may want to reconsider her endeavor and await further analysis.

Despite the dataset having over 4,100 different Kickstarters to analyze, there were only 1,047 that were plays. Furthermore, 720 of these 1,047 plays had goals of under $5,000, a whole $7,000+ less than what Louise is expecting. It is difficult to compare Kickstarters of vastly varying sizes, especially when there is a clear trend that smaller endeavors have higher success rates. The category and goal range of Louise's project make it difficult to combine the ideas from both analysis one and two as there are only 72 data points to work with. If you spread these 72 points into 12-month categories, there would only be an average of six data points per month. Although this is worth investigating, it should be used with caution as the sample size is becoming dangerously small when divided as such.

Going forward, Louise would benefit from charts that:
 - analyze outcomes based on goal for a much tighter windows, say her goal of $12,000 +- $3,000
 - analyze the subcategory "play" outcomes by launch date, and not just the parent category "theater"
 - analyze year of launch, partially because Kickstarter has become more well known since its release
 - further break down the subcategory plays into genres, which would likely need to use all of the data to look for general trends
