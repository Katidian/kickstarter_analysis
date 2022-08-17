# Kickstarting with Excel

## Overview of Project

### Purpose

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

### Analysis of Outcomes Based on Goals

### Challenges and Difficulties Encountered
Added a column (T) to the Kickstarter data to extract the month names from the launch dates in column S.
=TEXT(S2,"mmmm")

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

- What can you conclude about the Outcomes based on Goals?
Kickstarter campaigns for plays have the highest chance of success if they set the fundraising bar very low. More than three-quarters of plays targeting less than 
$1,000 achieved their goal. Success rates steadily fall as the goal sizes increase, and the percentage of failed campaigns actually starts to exceed that of successful
campaigns at around the $15,000 goal mark. Successes do not start to exceed failures on a relative basis until the $35,000 goal threshold. There we see another 
sweet spot; about two-thirds of campaigns that target $35,000 to $45,000 managed to achieve their goals. After that, however, success is much harder to come by. 
The percentage of successful campaigns nosedives for those seeking $45,000 or more.

- What are some limitations of this dataset?
Narrowing our kickstarter data down to only plays leads to very small sample sizes, particularly when it comes to projects with higher goals. In the play
category, for example, only 37 projects targeted $30,000 or more, compared to 186 projects in the sub-$1,000 category alone. We should take the 
$35,000-to-$45,000 "sweet spot" mentioned above with a grain of salt, so to speak, as only nine total play projects had goals in that range.


- What are some other possible tables and/or graphs that we could create?
Could show theater outcomes based on goals and play outcomes based on launch date
