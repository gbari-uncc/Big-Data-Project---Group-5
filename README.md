# Big-Data-Project---Group-5

## Deliverable 1:

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

## Deliverable 2:

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


## Deliverable 3:

## - Analytics and Machine Learning and Optimization and Results

<img width="925" alt="image" src="https://user-images.githubusercontent.com/97850156/207449977-f65b0554-e691-4f5e-a3e5-e133c355b38e.png">

<img width="917" alt="image" src="https://user-images.githubusercontent.com/97850156/207450170-94228c5c-dc1b-4f59-9b55-944d9dd454a4.png">

<img width="922" alt="image" src="https://user-images.githubusercontent.com/97850156/207450277-d16ee64a-d4ca-4271-adb9-cd7dd7207301.png">

<img width="923" alt="image" src="https://user-images.githubusercontent.com/97850156/207450381-dab0f9cc-03b0-48e6-94dc-7874029c2bd2.png">

<img width="915" alt="image" src="https://user-images.githubusercontent.com/97850156/207451172-78486678-6d02-4518-a9ff-1877c2f7308a.png">

<img width="926" alt="image" src="https://user-images.githubusercontent.com/97850156/207452836-7ce7cc8e-b23d-4d24-ac9d-0c0ce2cd3cd1.png">

<img width="925" alt="image" src="https://user-images.githubusercontent.com/97850156/207452908-87401957-e5eb-4bf7-84f6-86147fe40d4c.png">

<img width="932" alt="image" src="https://user-images.githubusercontent.com/97850156/207452980-63b0bfde-5e13-4a4f-bb81-10ab08e8ef12.png">

<img width="923" alt="image" src="https://user-images.githubusercontent.com/97850156/207453052-093f7aa9-433a-482a-8187-b732518827da.png">

<img width="923" alt="image" src="https://user-images.githubusercontent.com/97850156/207453112-8624d7e7-5b03-40af-ae88-dc7d65f94b87.png">

<img width="925" alt="image" src="https://user-images.githubusercontent.com/97850156/207453180-21252dbb-bc44-4909-995c-bce07badb5fc.png">

<img width="922" alt="image" src="https://user-images.githubusercontent.com/97850156/207453235-21eabb12-42be-4310-accb-6153c755989c.png">

<img width="929" alt="image" src="https://user-images.githubusercontent.com/97850156/207453307-443ee3da-cc6b-4832-9d81-f8448bd12f3d.png">

```html
             0
0    20.176585
1   208.581594
2   426.553412
3    16.410661
4    22.687018
5    18.051113
6    50.080698
7    49.147168
8    19.351202
9    63.511906
10   23.850544
11  190.597907
12   19.959836
13   44.020083
14   16.563783
15   14.374764
16   33.403286
17   14.397641
18   50.776503
19   37.195911
20   83.182348
21   25.566673
22   20.618916
23   14.275758
24   38.672630
25   63.653597
26   32.377515
27   64.327716
28   20.046318
29   34.684758
30   22.970605
31   38.513460
32  122.970126
33   29.906043
34   23.689658
35   12.514527
36   18.191116
37   71.391931
38   31.888733
39   23.355439
40   29.525741
41   34.726918
42   11.939698
43   37.616881
44   31.355444
45   25.944583
46   98.901231
47   26.847189
48   19.450522
49   13.278765
MSE = 116.02060520253548
```

<img width="920" alt="image" src="https://user-images.githubusercontent.com/97850156/207453493-cb58d592-246d-402b-b77b-3fab93e2683f.png">

```html
             0
0    23.619310
1   172.000000
2   411.333333
3    23.619310
4    23.619310
5    23.619310
6    38.568330
7    38.568330
8    23.619310
9    60.448000
10   23.619310
11  172.000000
12   23.619310
13   38.568330
14   23.619310
15   23.619310
16   38.568330
17   23.619310
18   38.568330
19   38.568330
20   89.305556
21   23.619310
22   23.619310
23   23.619310
24   38.568330
25   60.448000
26   38.568330
27   60.448000
28   23.619310
29   38.568330
30   23.619310
31   38.568330
32  121.500000
33   23.619310
34   23.619310
35   23.619310
36   23.619310
37   60.448000
38   38.568330
39   23.619310
40   23.619310
41   38.568330
42   23.619310
43   23.619310
44   38.568330
45   23.619310
46   89.305556
47   23.619310
48   23.619310
49   23.619310
MSE = 747.5768280988062
```
<img width="863" alt="image" src="https://user-images.githubusercontent.com/97850156/207453683-ec698e6f-718e-4a81-a54a-82f543df2161.png">

![image](https://user-images.githubusercontent.com/97850156/207478832-fb9aff05-ef52-4811-8139-6bd67e47dd17.png)

<img width="869" alt="image" src="https://user-images.githubusercontent.com/97850156/207453772-11698609-ea0b-43bd-9f03-7cf343134cf1.png">


<img width="870" alt="image" src="https://user-images.githubusercontent.com/97850156/207453833-7d4c612c-87db-476a-ac4f-e836d71a1f0a.png">

 -- Future Work
 
1. What was unique about the data?  Did you have to deal with imbalance? What data cleaning did you do? Outlier treatment?  Imputation?
It was challenging to work with millions of rows of flight delay data. We had to do rigorous and uniform data transformation and cleansing to remove null values and outliers from our data. We also had to reduce our dataset columns count and only keep key columns which would affect and be important during our visualizations.

2. Did you create any new additional features / variables?
Yes, we had to create additional feature during the data preparation and understanding stage. Our source dataset was a single file with size ~5GB so we had to break it down into chunks and clean each batch separately to remove outliers. Once completed, we then merged all these batches into a unified single file which was then used for data visualizations and machine learning model building. AWS Sagemaker notebook instances have a strict size restriction so we had to be careful and ensure notebook instance doesn’t crash. To overcome this limitation, we had to break our dataset into parts and then unify it later.

3. What was the process you used for evaluation?  What was the best result?
We used Linear regression and Decision Tree Regression supervised learning techniques for building our machine learning model. We got 83% accuracy using linear regression and 84% accuracy using Decision Tree Regression. 

. What was unique about the data?  Did you have to deal with imbalance? What data cleaning did you do? Outlier treatment?  Imputation?
It was challenging to work with millions of rows of flight delay data. We had to do rigorous and uniform data transformation and cleansing to remove null values and outliers from our data. We also had to reduce our dataset columns count and only keep key columns which would affect and be important during our visualizations.
. Did you create any new additional features / variables?

Yes, we had to create additional feature during the data preparation and understanding stage. Our source dataset was a single file with size ~5GB so we had to break it down into chunks and clean each batch separately to remove outliers. Once completed, we then merged all these batches into a unified single file which was then used for data visualizations and machine learning model building. AWS Sagemaker notebook instances have a strict size restriction so we had to be careful and ensure notebook instance doesn’t crash. To overcome this limitation, we had to break our dataset into parts and then unify it later.

3. What was the process you used for evaluation?  What was the best result?
We used Linear regression and Decision Tree Regression supervised learning techniques for building our machine learning model. We got 83% accuracy using linear regression and 84% accuracy using Decision Tree Regression. 

4. Is there Bias in your work? What were the problems you faced? How did you solve them?
We have worked collectively by allocating different tasks to different team members and worked collectively to resolve any roadblocks when occurred.

5. What future work would you like to do? 
We want to apply other regression models or machine learning to our data to identify better accuracy and reduced mean square error.

6. Instructions for individuals that may want to use your work
People interested in using our work could keep below points in mind which would help them in implementing similar results:-
Install necessary python libraries primarily Numpy, Pandas, MatPlotlib, Sns and sklearn which are heavily used in this project implementation.
Perform thorough data cleansing, transformation and preparation so as to ensure most of the outliers are removed from the dataset. This would give accurate visualizations and machine learning model accuracies.




