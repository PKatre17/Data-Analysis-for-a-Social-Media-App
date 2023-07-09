# Data Analysis for a Social-Media App Using Advanced Excel
### This was an Accenture Virtual Internship provided by Forage

<img width="260" alt="image" src="https://github.com/PKatre17/Data-Analysis-for-a-Social-Media-App/assets/97483777/4d8f0521-95ba-4147-847f-780b95f6e773"><img width="260" alt="image" src="https://github.com/PKatre17/Data-Analysis-for-a-Social-Media-App/assets/97483777/0201651f-35a6-4c6a-9fe6-0602c08f49ec">

Social Buzz, a content-focused start-up has reached over 500 million active users monthly. 
They have scaled quicker than anticipated and need the help of an advisory firm to oversee their scaling process effectively.

## Key Insights:
 - **16 unique** categories of content available
 - **"Animals"** is the most popular category having 1897 reactions.
 - **January 2021** was the month with the most posts (1708 posts).
   
## Objective:  
To start the engagement with Social Buzz, Accenture is running a 3-month initial project. They are expecting the following:
  - An analysis of their content categories that highlight the top 5 categories with the largest aggregate popularity.
  - An audit of their big-data practice. 
  - Recommendations for a successful IPO.
              
## Identified Problem:
Due to their rapid growth and the digital nature of their core product:
  - A huge amount of data is generated every day. 
  - over 100,000 pieces of content, including text, images, videos, and GIFs are posted. 
  - Highly unstructured data requires extremely sophisticated and expensive technology to manage and maintain. 
  - Not enough employees to maintain this highly complex technology. 

## Process:
 - Data Understanding
 - Data modeling
 - Data Analysis
 - Uncover Insights
   
## Data Model: 
Below were the tables:
 - User Table
   ID: Unique ID of the user (automatically generated)
   Name: Full name of user
   Email: Email address of user
 - Reaction Table
   Content ID: Unique ID of a piece of content that was uploaded
   User ID: Unique ID of a user that exists in the User table who reacted to this piece of content
   Type: A string detailing the kind of reaction this user gave
   DateTime: The date and time of this reaction
 - Content Table
   ID: Unique ID of the content that was uploaded (automatically generated)
   User ID: Unique ID of a user that exists in the User table
   Type: A string detailing the type of content that was uploaded
   Category: A string detailing the category that this content is relevant to
   URL: Link to the location where this content is stored
<img width="600" alt="Screenshot 2023-07-09 at 3 02 30 PM" src="https://github.com/PKatre17/Data-Analysis-for-a-Social-Media-App/assets/97483777/9e002d9c-8ccc-4085-8577-8160693212e5">

## Insights:
<img width="600" alt="Screenshot 2023-07-09 at 3 02 30 PM" src="https://github.com/PKatre17/Data-Analysis-for-a-Social-Media-App/assets/97483777/cf3f7b9d-0fa9-4e03-80d7-7911bbdb2879">
<img width="600" alt="Screenshot 2023-07-09 at 3 02 30 PM" src="https://github.com/PKatre17/Data-Analysis-for-a-Social-Media-App/assets/97483777/fca5f929-37ac-4404-8be4-e8cf5047aae2">
<img width="600" alt="Screenshot 2023-07-09 at 3 02 30 PM" src="https://github.com/PKatre17/Data-Analysis-for-a-Social-Media-App/assets/97483777/d72c1c86-80ff-4eac-b401-3b4f183a4d0a">









