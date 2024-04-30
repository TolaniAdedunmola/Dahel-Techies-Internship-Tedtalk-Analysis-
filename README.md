# Dahel Techies Internship Tedtalk Analysis
Tedtalk provides information about talk delivered at TED Events which includes Topics ,speaker,Date of Events,Number of views and Likes,Link to video. 


# Content 
[Project Overview](#project-overview)

[Data Dictionary](#data-dictionary) 

[Data Source & Tools](#data-source)

[Data Processing](#data-processing)

[Dashboard](#dashboard) 

[Insight](#insight)

[Recommendation](#recommendation)

# Project Overview 
The Tedtalk Analysis aims at uncovering Insight,pattern and trend tnto viewers engagement,speaker influence and Topic popularity.The questions to be answered are:

-	What is the total number of Authors?

-	What is the total number of likes and views?

-	What is the topic with the highest views and likes

-	What is the average likes per views?

-	Which of the authors hosted the most talk?

-	Trend of views across the year?

-	What is the correlation between views and likes?
  

  
  

# Data Dictionary 

| Column   | Description                                            | Data Type |
|----------|--------------------------------------------------------|-----------|
| Title    | The title of the TED Talk                              | Text      |
| Speaker  | The name of the speaker(s) who delivered the TED Talk  | Text      |
| Date     | The date when the TED Talk was delivered               | Date      |
| Views    | The total number of views received by the TED Talk     | Integer   |
| Likes    | The number of likes or positive reactions received     | Integer   |
|          | by the TED Talk from viewers                           |           |
| Link     | The URL or hyperlink to the TED Talk video             | Text/URL  |


# Data Source 

This dataset was compiled by Dahel Techies for internship purpose.
Download [Here](https://docs.google.com/spreadsheets/d/1LZx_TUD3n2v5OdXEjFFKqI3Dbt4FjYIp/edit?usp=drivesdk&ouid=115085326801434600917&rtpof=true&sd=true)

# Data Processing 

➢The Dataset was Transformed in the Power Query.

➢No cleaning was done as the column quality was 100%, the data types were 
accurate, 1 duplicate value was found and no empty rows.

➢The Data was then loaded into Power Bi.

➢Dax was created for Total Likes, Total Views, Total Talks and Average Views Per talk.


# DashBoard


<!-- Banner Text -->
<img src="https://github.com/TolaniAdedunmola/Dahel-Techies-Internship-Tedtalk-Analysis-/blob/main/Tedtak%202%20analysis.PNG">



# Insight
Between January 1, 1970 to February 1 2022, a total number of 5540 Ted Talk was published. 
-	It has a total of 341 million likes and 11 billion views.
-	The average likes per view is 3.04%
-	There’s 4443 Authors between those years with Alex Gendler being the author with the most topics (Authored 45 topics). Iseult Gillespie is the 2nd author with the most ted talk.
-	The topic “Do skills kill creativity?” has the highest number of likes and views followed by “your body language may shape who you are” having the second most liked and most viewed topic
-	From the findings there’s a correlation between likes and views, the more the views, the higher the likes. 
-	The lowest number of view was in the year 1970 this might be as a result of technology not being widespread then, the highest views happened in the year 2015


# Recommendation

Based on the findings from the analysis of TedTalk data, here are some recommendations:

1. *Content Diversity*: Encourage a diverse range of topics and speakers to maintain audience engagement and cater to varied interests.

2. *Speaker Recognition*: Recognize and promote speakers who consistently deliver high-quality talks and generate significant viewer engagement, such as Alex Gendler and Iseult Gillespie.

3. *Popular Topics*: Explore producing more content around popular topics like "Do skills kill creativity?" and "Your body language may shape who you are" to capitalize on existing audience interest.

4. *Correlation Awareness*: Be mindful of the correlation between likes and views, leveraging this insight to gauge audience sentiment and tailor content accordingly.

5. *Historical Trends*: Consider historical trends in viewership to understand shifts in audience preferences and adapt content strategies accordingly. For instance, the significant increase in views from 1970 to 2015 indicates a growing audience and interest in TedTalk content over time.

6. *Engagement Metrics*: Continue to monitor and analyze engagement metrics such as likes and views to assess the effectiveness of content and identify areas for improvement.

By implementing these recommendations, TedTalks can continue to deliver compelling and impactful content that resonates with a broad audience while maintaining relevance and engagement over time.


.......Thank you for your Audience.


