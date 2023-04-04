# Cyclistic-Bike-Share-Case-Study
In this project, I analyzed data for the marketing team to Identify the main differences between two types of customers the casual and annual riders, and use digital media to influence them. 

# Introducion
### Scenario
I am a junior data analyst working in the marketing analyst team at Cyclistic, a bike-share company in Chicago (Fictional company). The director of marketing believes the company’s future success depends on maximizing the number of annual memberships. Therefore, my team wants to understand how casual riders and annual members use Cyclistic bikes differently. From these insights, my team will design a new marketing strategy to convert casual riders into annual members.

### About the company
In 2016, Cyclistic launched a successful bike-share offering. Since then, the program has grown to a fleet of 5,824 bicycles that are geo tracked and locked into a network of 692 stations across Chicago. The bikes can be unlocked from one station and returned to any other station in the system at any time.

### Moreno (Marketing manager) has set a clear goal:
Design marketing strategies aimed at converting casual riders into annual members.
In order to do that we in the marketing analyst team need to better understand how annual members and casual riders differ, why casual riders would buy a membership, and how digital media could affect their marketing tactics. Moreno and her team are interested in analyzing the Cyclistic historical bike trip data to identify trends

# My process In Analysis
In order to answer the key business questions, I will follow the steps of the data analysis process: ask, prepare, process, analyze, share, and act

# About The Data
This dataset is the first-party data collected from its organization and located in 12 CSV files; every file represents a month from the 2022 year, organized into 13 columns. There is no biased or credibility in this data because this is first-party data. This data is ROCC (Reliable, original, comprehensive, current, and cited)

# ASK
#### Three questions will guide the future marketing program:
- How do annual members and casual riders use Cyclistic bikes differently?
- Why would casual riders buy Cyclistic annual memberships?
- How can Cyclistic use digital media to influence casual riders to become members?

#### Business Task
- Identifying the main differences between casual and annual riders and using digital media to influence them

# Prepare and clean data
#### In This stage, I prepared the data for analysis by doing these steps
- Calculating the ride length and the day of the week by using spreadsheets
- Merging 12 CSV files into one file to make a full-year analysis by using python
- Dropping Nulls value
- transforming the data type of end date and start date to date type
- I dropped the ride_length and make a new one in minutes in integer type
- I dropped the start station name id and the end station name Id
- Removing negative and zero values of ride length
- Create a monthly column by extracting it from the start date
- I checked the duplicated rows
- Make sure the columns are consistent
- Saving cleaned data into a new CSV file ( to use it for visualization)
 
 # Analysis 
 - I make the analysis using python with jupyter Notebook

# Recommendations
#### This recommendation I get after anlyze the data
- I suggest making a summer subscription to attract casual users.
- Where the casual members' ride length is more than the annual subscriber, the casual riders use the bike on weekends and in summer. We can customize a new subscription for casual users.
- Whereas the casual subscribers used the docked type cycle, We can make an offer when they use the docked type in an annual subscription.
- Using Digital media to clarify the benefits of subscribing to the membership for riders who have a long ride length
 
# Share 
I make a presentation to communicate the findings with the stakeholders
[Show the presntation](https://docs.google.com/presentation/d/1FW8uAhTC0ElLVwDJYVzaKG3bmdVpdNy1mFRzQZynOQk/edit?usp=sharing)

# Note 
This data is part of Google data analytics certificate project
