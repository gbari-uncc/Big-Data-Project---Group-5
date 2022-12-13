# Big-Data-Project---Group-5

## 1) Team:-

  ###   a)  Members: 
            Saumit Chinchkhandi - 801305320
            Mahesh Hasbi - 801315534
            Thanmaiye Namburi - 801281518
            Gautham Raj Bari - 801274985
            Mounika Gottumukkala - 801276287
            
  ###   b)  Communication plan to include project artifact repository:
          - Github Repository link: https://github.com/gbari-uncc/Big-Data-Project---Group-5.git
          - Project notes link: https://docs.google.com/document/d/1a1OeyMk7v8ahIMrTptckOU3W4sFB-7zqB1-u46igZFE/edit
          - As a team, we have decided to follow up virtually through Google Meet or Zoom every Thursday for analyzing ongoing project feature additions and solving issues that might surface during the development. 
          - Every Tuesday after class, we have planned to meet offline for around 30 minutes to 1 hour to discuss and assign the next project deliverables among the team.

## 2) Business Problem or Opportunity, Domain Knowledge (link to information on domain relative to data, problem or opportunity):-
  > Flight Delay Prediction Data is a repository that houses crucial, flight schedules information like Origin and Destination Airport details,Flight Number, Flight schedules in (date,month,year), Operator Airlines, Delays,On-Time arrivals and departures and much more for various flight operators worldwide. Additional details about flight cancellations and the cancellation reason, flight diversions, weather and carrier delays contributing to delays is also covered in the dataset. The flight delay prediction is updated frequently thus solidifying authencity and coverage of new flight statistics.
  > Our group intends to visualize relationships between various flight parameters and generate insights about the data for various flight operators and flights. Through this we would understand if there are any underlining trend which is being followed and also discover any outliers if present. This detailed data driven analysis will help us identify key patterns and draw conclusions which could be pivotal in predicting future flight patterns.
  >  We will create dashboards and plot different parameters across bar,pie and other visualization charts. We also aim to figure out any important conditions directly or indirectly causing delays. 
    
## 3) Selection of relevant data from the sample datasets for AWS Sagemaker:-
 
 ### Flight Delay Prediction | Kaggle ([https://www.kaggle.com/datasets/whenamancodes/flight-delay-prediction](https://www.kaggle.com/datasets/robikscube/flight-delay-dataset-20182022?select=Combined_Flights_2022.parquet))
 

## 4) Research Objectives and Question(s) 

  ### Objectives:
    > - Use Amazon Web Services(Simple Storage Service(S3) for storing our dataset, AWS Glue for crawling the data to generate tables and schemas, Jupyter Notebook for Data Preparation and Cleansing) for analysis of the Flight Delay Prediction dataset.
      - Extract meaningful insights by developing key performance indicators (KPI's) which highlight key attributes which are essential for evaluating business functionality, gauge performance of different airlines and identify patterns among the data. 
      - Designing detailed and engaging dashboards for visualizing our derived conclusions after analysis using Amazon QuickSight.

  Questions:
  - > Number of flights On-Time, Delayed, Cancelled, Diverted per month,per quarter and per year between 2018-2022. 
  - > Which Airline Operators flights are Delayed, Cancelled currently and will most likely experience delays in the future? Identify any paramters causing these  delays
 - > Which Origin and Destination airports are the most and least effecient based on number of flight cancellations, delays etc.
  - > Plotting ArrivalDelay and DepartureDelays values for different flight operators on a monthly basis to determine patterns and trends across several years.
  - > Analyze YoY increase or decrease in flight On-Time, Cancellations, Delays and Diversions.
  - > Using Machine Learning for predicting percentage of flights Arrivals and Departures On-Time, Delayed, Cancelled, Diverted in the next years based on current flight trends. 
 
  
Note: The scope of the questions might change as we further dwell into the project.


## 5)  Data Preparation

 - We uploaded the data into S3 bucket.
 - We used AWS s3 copy command to load the data into Jupyter notebook instance. 
 - Combined the data into a combined dataframe.
 - <img width="857" alt="image" src="https://user-images.githubusercontent.com/97850156/200449617-42702e5a-c401-4049-a5c3-ea38d781df22.png">
 - <img width="847" alt="Dataprep" src="https://user-images.githubusercontent.com/97850156/201775342-8c0ef819-20dd-4d39-a7f7-02c46526dfe0.png">


## 6)  Data Understanding
- We used Numpy and Pandas to understand and explore the data.
<img width="314" alt="image" src="https://user-images.githubusercontent.com/97850156/200449876-59bf321f-1921-4831-816f-fdc91fafa860.png">
<img width="565" alt="Data" src="https://user-images.githubusercontent.com/97850156/201775389-a120e463-a8f4-4cbe-a462-6a801dc1e2f6.png">
[Dashboard.pdf](https://github.com/gbari-uncc/Big-Data-Project---Group-5/files/10007388/Dashboard.pdf)

- <img width="769" alt="image" src="https://user-images.githubusercontent.com/97850156/200449947-73900dce-4e58-4b01-9d8f-da894d9cbb50.png">

<img width="772" alt="image" src="https://user-images.githubusercontent.com/97850156/200449996-46cf9a2b-614c-4905-9b25-552c903e2bac.png">

<img width="769" alt="image" src="https://user-images.githubusercontent.com/97850156/200450026-6ef0ca6c-73c8-4886-a456-67a33466ec81.png">

<img width="686" alt="image" src="https://user-images.githubusercontent.com/97850156/200450063-b944dddd-00c2-4116-9d10-452963ace2d6.png">

<img width="683" alt="image" src="https://user-images.githubusercontent.com/97850156/200450102-a9a1e67d-17af-4dcd-9a14-1d6775bf839e.png">

<img width="683" alt="image" src="https://user-images.githubusercontent.com/97850156/200450125-288d5b34-af00-4b4d-8b15-cd3a7d780413.png">

![image](https://user-images.githubusercontent.com/97850156/200450142-753ce72f-ed43-4665-a55f-015c6e1be8b4.png)

<img width="686" alt="image" src="https://user-images.githubusercontent.com/97850156/200450173-64f76cce-8d24-4132-9bd1-6c4afca83b1f.png">


