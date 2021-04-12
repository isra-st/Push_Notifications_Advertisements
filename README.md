# ADVERTISING PUSH NOTIFICATIONS PERFORMANCE

Ironhack Data Analytics Bootcamp - Final Project - Real problem Statement and dataset from OutPush. 

1. Introduction to outpush
2. Problem statement
3. Conclussions
4. Presentation

# 1.Introduction to <img src='https://outpush.co/wp-content/uploads/2021/02/Outpush-Logo-3.png' width="142.5" height="35.63">

* Push-notifications ads network
* Launched in december 2020
* Middleman between advertisers and publishers

How does it work?
* Clients install a module
* Outpush send personalised ads to the client users
* 1 click = money for the client

# 2. Problem statement

Subscribers receive same notifications multiple times: is it usefull?

Challenges of this project:

  * Understand how do repeated impressions affect users ‘Click Through Rate’ over time
  * Perform statistical analysis

*‘Click Through Rate’ = Number of clicks on Ads / Number of impressions of the Ads

# 3. Insights and recommendations

Boost the notification push during the time periods with higher subscribers activity:

  * Wednesdays, the higher 'Click Through Rate' of the week
  * Saturdays, the lower 'Click Through Rate' of the week
  * Between 09:00 AM and 11:00 AM the higher 'Click Through Rate' of the day
   
Subscribers lose interest on the ads embeded in the noticitions over the time: 
  * A subscriber “interest retention” plan could help to boost the Ads 'Opened Rate' for longer time subscribed users.
 
 
    <img src='https://user-images.githubusercontent.com/73388089/114279532-79107d00-9a35-11eb-8d98-8ea4c563d4ce.png' width="440" height="320">

The optimal number of Ads repetition should  be in average 4:
 * CTR decreases after every repetition of the Ads.  
   * 1st impression: 17.9%
   * 4th repetition: 7.1%
   
   
   <img src='https://user-images.githubusercontent.com/73388089/114280100-140a5680-9a38-11eb-98e8-b71be9f0b056.png' width="440" height="320">
   
* The probability of opening the Ads decrease after every repetition
  * Probability on the 1st impression: 0.8%
  * Probability on the 4th repetition: 0.3%
   
   
  <img src='https://user-images.githubusercontent.com/73388089/114280171-5b90e280-9a38-11eb-8786-94d868ced90f.png' width="440" height="320">
  
* The conditional probability of clicking the add, given it was not opened before, drops from 0.79 in the first impression to 0.38 in the 4th repetition.

  <img src='https://user-images.githubusercontent.com/73388089/114280185-69466800-9a38-11eb-8a7f-ffc77e0fb0b2.png' width="440" height="320">


# 4. Presentation

To see the presentation, click in the below picture.

[![Customer Segmentation_Github](https://user-images.githubusercontent.com/73388089/114280289-da861b00-9a38-11eb-80ab-54801e271918.png)](https://github.com/isra-st/Push_Notifications_Advertisements/files/6290494/Outpush.-.Ironhack.-.Final.project.pptx)



