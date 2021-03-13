# Kickstarting with Excel

## Overview of Project
---
This project is meant to analyze the outcomes of theater kickstarters by the time of the year the kickstarter was started, and the fundraising goals in USD. 
The data was first looked at based on the Month that the theater kickstarter was started. Then the data was broken down based on the fundraising goal for each kickstrater by 5000 dollar incriments. 
By doing this, it will be possible to see when is the optimal time of the year to start a theater kickstarter, as well as what would be the optimal fundraising goal. 
---
### Purpose

## Analysis and Challenges
---
In order to properly analyze the data, first it was put into an excel pivot chart Filtered by the parent category of play (in this case theater was the category) and the year that the fundraiser began.
Then put outcomes in columns, Date Created Conversion into rows, and the Count of the fundraising outcomes in values. A line chart was then created based off the values for us to analyze (See attached image below).
For outcomes based on goals, A new worksheet was created and sorted based on fundraising goal size by 5000 dollar increments, successes, failures, and the percentage of each kickstarter that suceeded and failed. 
This data was then put into a line chart for further analyzation (see attached image). 

### Analysis of Outcomes Based on Launch Date
---
![Outcomes based on kickstarter launchdate](https://github.com/TCJester10/kickstarter-analysis-Tessa-Cayton/blob/main/Resources/Theater_outcomes_vs_Launch_Tessa.png)
---
Based on this image, we can see that there are generally more successes than failures, and very few cancelations. 
In the first few months, success and failures follow each others trends with about 20-30 more successes.
Then in April and especially May, the successes far outpace the failures with many more showing up, while failure numbers stay about the same with only a slight uptick.
After peaking in May, the successes consistantly fall each month until September. Whereas Failures stay about the same throughout the extended summer. 
In the fall, failures tick up, but don not pass successes until they come even in December. 

### Analysis of Outcomes Based on Goals
---
![Outcomes based on Goals](https://github.com/TCJester10/kickstarter-analysis-Tessa-Cayton/blob/main/Resources/Outcomes_vs_Goals_Tessa.png)
---
Based on this image of the percentage of success vs. failures based on fundrasing goal, there is a trend that generally the lower the goal more likely it is to succeed up to 15000 dollars or so.
Failures become more prevelent until 35-40000 dollars which sees successes overtake failures, and then after failures far surpass successes. 
It should be noted that the data for this is very skewed. There are hundreds more kickstarters aiming for goals below 20,000 dollars, and thus provide a much steadier dataset to look at. 

### Challenges and Difficulties Encountered
---
The analysis based on start date was pretty simple. 
It should be noted that in the dataset there is a consistent distribution (though more do show up from May to August), and that the dataset does not appear to be influenced by outliers or insncere data.
For the Outcomes based on goals, the data is very volitile due to a low number of high price goals. The data is much steadier in the lower goal brackets. 
## Results

# What are two conclusions you can draw about the Outcomes based on Launch Date?
---
That generally the Summer months starting from May and foing until September see more successes than failures. It would be best to start your fundraiser during April or a time soon after. 
This is likely due to more time off and better weather that would encourage more patronage to theaters. 
School being out also likely helps. 
---
# What can you conclude about the Outcomes based on Goals?
---
That goals should be kept below 15,000 dollars. Some successes exist above this, but it is much more likely for a smaller goal to be met. 
One reason the highest goals might see such failure that they do is that they aren't really for plays. 
---
![All fundraisers with goals above 1,000,000 dollars](https://github.com/TCJester10/kickstarter-analysis-Tessa-Cayton/blob/main/Resources/above_1%2C000%2C000.png)
---
As seen, many fundraisers for goals above 1,000,000 dollars were for building or renovating theater spaces rather than putting on a play. 
It should also be noted that fundraisers such as *Join us in creating a new Hell on Earth!* and *Capricorn Horn- Entertainment for the World's Finest Gents* might not be the most serious of attempts. 
Either way, I believe it is best to say that a lower goal is better and much more manageable. Escpecially if it is below 15,000 dollars. 
It is interesting to note that the 35,000-40,000 dollar bracket saw successes overtake failures. This is likely just due to a lack of data though. 
# What are some limitations of this dataset?
---
That it is pretty basic. We can see when is the best time to start fundraisers, and we can also see what is the best goal to aim for, but we don't see anything about fundraiser quality, how much each individual donation was, or how many donations it took. 
We also have data for building new theater spaces mixed in with theatrical productions, further sepeartation of the data would make for better analyzation. 
---
# What are some other possible tables and/or graphs that we could create?
---
A thourough look into how much money was raised by each donation. Essentially, was each success funded by a lot of people? Or a few big doners. 
A box and whisker plot would be good too, as it would remove some of the higher outlier values for fundraisers that seek to build/renovate theater spaces. 
