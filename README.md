# YouTube_Views_Prediction

![Project Image](https://1.bp.blogspot.com/-QmorW9uzfJo/X4VnZF86rkI/AAAAAAAAA0Y/8pv8AFEmlCYo45SSKWtMmrBxaqI_rliDACLcBGAsYHQ/s655/ytviews.jpg)

> **How to get more views on your own channel ?**

-----

### Table of content's:
your selection header will be used to reference location of destination.
- [Short Project Blurb](#Short_Project_Blurb)
- [Goals](#Goals)
- [Matrics](#Matrics)
- [Conclusion and Recommendation](#Conclusion_and_Recommendation) 
- [Author info](#Author_info)
 
-----

## **Short Project Blurb**
   Two things that needed in the monetization process for a YouTube channel is to have 4000 hours of broadcast time for 12 months and have a minimum of 1000 subscribers. To get the terms of the length of broadcast hours, visitors are not only sought to be able to visit but they must be able to watch as long as possible on our content. The importance of a high number of views will greatly support the amount of time the content appears.
   The data used in this analysis comes from YouTube statistics in India consisting of 36790 data and 1390 Channels collected in December 2017-June 2018. Based on this data, it raises the question of **_how can we be successful in building a YouTube channel in India?_**. This will be answered by analyzing the characteristics of users who come from India and ensuring that several important parameters must be formed as perfect as possible. So this is the background for analyzing the YouTube views data in order to find tips and tricks to produce a quality YouTube channel with lots of views.

-----
## **Goals** : 
- Help others to having tips and trick for building channel YouTube in India based on features important.
- Know the carracteristics of people who had watched YouTube in India.
- Build Modeling.
-----

## **Matrics**:
- Data pickle of modelling.
- Percentage of impact from the most important features.

-------
## Modelling Result

| Evaluation\Model | Linear | DecisionTree | SVR | RandomForest |
| ---------------- | ------ | ------------ | --- | ------------ |
| MAE | 0.34 | 0.26 | 0.40 | 0.20|
| RSME | 0.44 | 0.36 | 0.52 | 0.26|
| R SCORE | 0.35 | 0.57 | 0.10 | 0.77|

Based on evaluation modelling result, RandomForest gave the better result than others. We could seen the low value of MAE and RMSE or high R Score. I had set Tunning hyperparameter with Random Grid search and the result gave the same thing like before.

----

## Conclusion and Recommendation

From Modelling we found some features that should be paying attention for create the channel to get more views. These features will shown in the image below and score representing the percentage of feature affect the views.

![Featue Important](https://github.com/FransRiantoni/YouTube_Views_Prediction/blob/main/Feature%20Important%20from%20Modelling.png)

These are a few solution or tips for create features perfecly.
1. Video Description Text Optimatization.
   We recommend to use 150-200 words including the keywords, links and suggestion to other videos that we have.
2. Categorize Videos
   Categorizing videos will help YouTube recommeding our Video to users in need. Even though, Sometimes it is hard to compare several categories that have similarities but the longer we post more videos YouTube will be able to determine the type of our video category. 

3. Jumlah dan Best keyword Tags
   Tagging your video with searchable words will make it more likely to appear at the top of search engines. we can use **SEMrush,Ahrefs, YouTube's Suggest dan Google Trend's YouTube** to analyis and get the best keywords and just select 15-30 tags for our content. Then We can put out tags on title, subtitles , dan video description. So, This is a good way to gross more views. 
   
Some Indication that we can use to see video will be get more viewers : 

1. Sum of Likes
   
   We also can add a button that represent the like such as **Like End Screens/UnLike End Screens** for get their participation and request to watch more videos.

2. Faster_Tranding
   
   The Tranding Video must have a large number of views. In this case,  it is necessary to look at the average time of video that can be seen by many people. If the time extent to tranding does not reach the value of views that should be, this indicates that the content will not have high views.


Final quote:
"The more time they spend on your videos, the more positive signals get sent to YouTube’s algorithm."




# Gracias

-----
# About Author 

[LinkedIN - Frans Riantoni](https://www.linkedin.com/in/frans-riantoni-purba/)

[Medium - Frans Riantoni](https://medium.com/me/stories/public)


---
