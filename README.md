# Kickstarter-analysis_1
Module One Challenge

# An Analysis of Kickstarter Campaigns 

## Overview
    This Project is about  **Louise**, who is starting a new crowdfunding campaign to help fund her play **FEVER**. She estimated her budget for campaign around           $12000. To gain better understanding of the project she seek out for help by power Excel user.
   
## Purpose
    I used Excel to organize, sort and analyze the crowdfunding data to generate the insight that will help Louise understand the campaign from start to finish and she     will be able to compare her campaign with other successful ones in the same category, and hopefully that altogather help Lousie in making smart decisions. 
   
 # Analysis And Challenges 
 
### Organize And Sorting Data
    Firstly, , I added filter in pledge, country, outcomes, and goal columns so that Louise project is going to be in US she can view the data as per her need.I added     some conditional formatting in the **outcome** column where successful=green, failed=red,live=blue, and canceled=yellow to provide **visual presentation** of the       data in the worksheet at a glance. 
   
### Percentage Funded
    I created a **Percentage Funded** column so that Louise can easily interpret the data and quickly determine how close a campaign came to 'reaching' and in some         cases'exceeding' their funding goal.Again I with the help of conditional formating I made **Maximum** percentage funded color **blue** and moving towards               **Minimum**    percentage **red**.
  
 ### Average Donation
    I also added "Average Donation" column. This column will help Louise set up her incentive by first determinig how much money people have pledged historically. 
   
# Challenges

## Categories Challenge 
    Their were two challenges for me to make the data more readable. The first one was the **Category and Subcategory** was merged togather, therefore initially it was     hard to be very specific with the information I want to provide. To overcome that hurdle I split them into two columns as **Parent Category** and **Subcategory**.
    Based on these categored I created a visual presentation in form of **Pivot Table** and **Chart**.
    
### Parent Category 
   I choose **Outcomes** to present the values based on the **Parent Category**. Also added **Country** in filter to enable Louise see the information country wise as    well. With the help of this **Pivot Chart**, Louise can easily analyze which Parent Category performed well and which ones did not. She can use filter added in the    chart to view the specific details of her desire that is if she wants to see the details only for theater she can choose from Rows **Theater** only and if she wants    to see specifically how theater performs in US, Loise can choose **US** from the country filter. I added this information in the new sheet and named it as **Parent    Category Statistics** in the work book.
   
   ![Parent Category Outcome](https://user-images.githubusercontent.com/105535250/174155268-958b014b-6b53-4ef2-b4df-b884a6af31a8.png)

    
### Subcategory
   As Lousie was creating a Play not the theater, I used the data from **Subcategory**  to create another **Pivot Table** and **Chart** that will help Louise to focus    her analysis on the area that is more relevant to her project. To do this, I choose **Outcomes** to present the values based on the **Subcategory**. Also added        **Country** and **Parent Category** in filters. This will privilege her to view the details as she like.  
    
![Subcategory Outcomes](https://user-images.githubusercontent.com/105535250/174155881-0c8ccb5b-adbd-4bd6-b376-dd6f5e7871b9.png)

  
### Time Format Challenge
    The Second challenge was the time. The data was orignally using **Unix timestamp**, which was not human readable format. By utilizing the converting formula I         changed the time format into human readable and added two more columns as **Date Created Conversion** and **Date Ended Conversion**. 
   
## Years
    Also, from the 'Date Created Conversion" column i extracted the years of the projects which can give a quick review to Louise about how many project took               place in same years. 
   
### Analysis of Outcomes Based on Launched Date
   Now that we already have the date range of each project I tried to provide Louise with additional visuailization of the Data for finding how well all the campaigns    performed based on the Launched Date. To do so, I created another Pivot Table and Chart. This time I used Line Chart to view the data. Line Charts are helpful when    trying to determine trends. Again I choose **Outcomes** to present the values on the basis od **Date Created Conversion** filtering by **Parent Category** and          **Years**. This way Louise can view the trend on monthly basis as well. 
   

   
   
   
 
   
   
