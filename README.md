# Kickstarting with Excel

## Overview of Project
To help Louise start her crowdfunding play “Fever,” we need to understand what factors, like the type of category) where the most successful in the past years.


### Purpose
Louise’s play came close to the fundraising goal in a short time. For these two specific analyses below, I could visualize the data in line graphs to see how her play’s outcome compares to others based on their launch date and funding goals. This method is an excellent way to measure her performance and see if she aligns with the other’s results for future projects.


## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
Using my knowledge from previous lessons, I followed the same steps to create a pivot table. I selected all of the data and made a new pivot table on a new page. I populated the pivot fields with the data’s outcomes and dates to visualize how many successful, failed, and canceled campaigns each parent category at every month.

### Analysis of Outcomes Based on Goals
In this section, I was able to come up with the count of successful, failed, and canceled at specific goal ranges by using the formula below:
 
=COUNTIFS(Kickstarter!$F:$F,"Successful",Kickstarter!$D:$D, ">=5000", Kickstarter!$R:$R, "plays",Kickstarter!$D:$D, "<=9999")
 
After selecting the Kickstarter data, I had to choose the outcomes column F so the formula could count how many were successful, failures, or canceled. After that, I had to select column D (the goal amount) to put in the outcome ranges. Between the degrees, I had to specify the categories “plays” so the formula could only count the outcomes for all the plays (which Louise is interested in).
### Challenges and Difficulties Encountered
One major challenge I faced in this module was the second deliverable. In the beginning, I was just plugging in the COUNTIF() function to see if I could get an outcomes. I was struggling because I didn’t know the purpose of the function, and I just wanted it to work for the sake of it. Once I started looking at other examples, I understood their meaning (to count how many were successful, failed, and canceled at specific goal ranges).

## Results

- What are two conclusions you can draw about the Outcomes-based on the Launch Date?
The film, theater, and music are the only three categories with a higher successful outcome throughout the months than failed outcomes.
The theater is open with the most successful outcomes out of all the categories, and it has had more success than failures every month for all nine years.
- What can you conclude about the Outcomes-based on Goals?
Once the goal amount increases, there are more failed than successful plays. There were no canceled plays, but it is essential to consider which range of fundraising goals are the most successful for future plays. This shows that people like Louise should be reachable and that there is a chance to succeed if you set a goal between 35,000 and 44,999.

- What are some limitations of this dataset?
When I was looking through the data, I saw that most of the plays were from the US and GB. This can shift the data because certain countries have specific preferences because of their cultures.

- What are some other possible tables and graphs that we could create?
Another graph we can create is one where it shows which county had the most successful outcomes every year.
