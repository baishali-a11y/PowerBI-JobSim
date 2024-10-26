# PowerBI-JobSim
PWC Switzerland PowerBI Job Simulation Call Center Data Analysis

About the Data:
The dataframe df1 has 5000 entries and 10 columns. Here is a brief description of each column:

Call Id: This is an object type column and it has no null values. It likely represents a unique identifier for each call.
Agent: This is an object type column and it has no null values. It likely represents the name of the agent who handled the call.
Date: This is an object type column and it has no null values. It likely represents the date of the call.
Time: This is an object type column and it has no null values. It likely represents the time of the call.
Topic: This is an object type column and it has no null values. It likely represents the topic of the call.
Answered (Y/N): This is an object type column and it has no null values. It likely represents whether the call was answered or not.
Resolved: This is an object type column and it has no null values. It likely represents whether the issue was resolved or not.
Speed of answer in seconds: This is a float type column and it has some null values. It likely represents the time taken by the agent to answer the call.
AvgTalkDuration: This is an object type column and it has some null values. It likely represents the average duration of the talk.
Satisfaction rating: This is a float type column and it has some null values. It likely represents the satisfaction rating given by the customer.

Analysis Done:
Created a dashboard in Power BI for Claire that reflects all relevant Key Performance Indicators (KPIs) and metrics in the dataset.
KPIs include:
Overall customer satisfaction
Overall calls answered/abandoned
Calls by time
Average speed of answer
Agent’s performance quadrant -> average handle time (talk duration) vs calls answered
