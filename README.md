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
 
 ### Flight Delay Prediction | Kaggle (https://www.kaggle.com/datasets/whenamancodes/flight-delay-prediction)
 

## 4) Research Objectives and Question(s) 

  ### Objectives:
    > - Use Amazon Web Services(Simple Storage Service(S3) for storing our dataset, AWS Glue for crawling the data to generate tables and schemas, Jupyter Notebook for Data Preparation and Cleansing) for analysis of the Flight Delay Prediction dataset.
      - Extract meaningful insights by developing key performance indicators (KPI's) which highlight key attributes which are essential for evaluating business functionality, gauge performance of different airlines and identify patterns among the data. 
      - Designing detailed and engaging dashboards for visualizing our derived conclusions after analysis using Amazon QuickSight.

  Questions:
  - > Number of flights On-Time, Delayed, Cancelled, Diverted per month,per quarter and per year between 2018-2022. 
  - > Which Airline Operators flights are Delayed, Cancelled currently and will most likely experience delays in the future? Identify any paramters causing these  delays
  > Which Origin and Destination airports are the most and least effecient based on number of flight cancellations, delays etc.
  > Plotting ArrivalDelay and DepartureDelays values for different flight operators on a monthly basis to determine patterns and trends across several years.
  > Analyze YoY increase or decrease in flight On-Time, Cancellations, Delays and Diversions.
  > Using Machine Learning for predicting percentage of flights Arrivals and Departures On-Time, Delayed, Cancelled, Diverted in the next years based on current flight trends. 
 
  
Note: The scope of the questions might change as we further dwell into the project.
