# Covid_Impact_on_Taxi_uses_in_New_York_City

-|- Objective: The project aims to analyze the impact of variables like fare amount, tip amount, total taxes duration, trip day, busiest location &amp; routes on taxi uses and their correlation with each other for month Feb 2020 and June 2020

-|- Tools and Techniques employed to solve the above problem: 
 - Pandas
 - Data Wrangling
 - EDA

-|- PACE strategy to implement the project
  - Planning: In this stage project workflow is outlined, objectives definition, data collection, tools requried for project, and update to stakeholders
  - Analyse: Data is scrubbed, converted and formated, and update to stakeholders
  - Construct: Model is constructed using pandas and tested for accuracy
  - Execute: Results are finalised, visualisations are prepared done and shared with stakeholdrs, Feedbacks are taken into consideration

-|- Insights founds from the analysis
  - June 2020 DataFrame shape is 8.73% compared to Feb 2020, this indicated that only around 8.73% of trips were taken in June 2020 compared to Feb 2020
  - Fare amount:
    o June month has higher variability in fare amount compared to Feb month
    o For longer duration trips fare amount is bit higher for June 2020 compared to Feb 2020
  - Fare amount vs. location
    o June 2020 (pick up)
      > 186 & 48 (max fare)	[186: Manhattan (Penn Station/Madison Sq West),	48: Manhattan (Clinton East)]
      > 236 & 237 (busiest)	[236: Manhattan (Upper East Side North), 237: Manhattan (Upper East Side North)]
    o	June 2020 (drop off)
      > 75 (max fare)			[75: Manhattan (East Harlem South)]
      > 236 & 237 (busiest)	
    o Feb 2020 (pick up and drop off)
      > 161 & 237 (max fare)		[161: Manhattan (Midtown Center)]
      > 161 & 236 (busiest)
  - Percentage of trips with 1 passenger increased and trips with 2 or more passengers decreased in June 2020
    o Feb 2020
      > 1 passenger (71.91), 2 passenger (14.83), 3 passenger (3.87), 4 passenger (1.85), 5 passenger (3.51)
    o	June 2020
      > 1 passenger (77.92), 2 passenger (11.46), 3 passenger (2.87), 4 passenger (0.99), 5 passenger (2.52)
  - Highest Taxi uses: Tuesday had highest taxi uses in June 2020 month while Saturday was the highest taxi use day for Feb 2020 month
  -	Duration vs. location
    o	June 2020 (pick up)
      > 186 & 48 (max duration)	[186: Manhattan (Penn Station/Madison Sq West),	48: Manhattan (Clinton East)]
      > 236 & 237 (busiest)		[236: Manhattan (Upper East Side North), 237: Manhattan (Upper East Side North)]
    o	June 2020 (drop off)
      > 75 (max duration)		[75: Manhattan (East Harlem South)]
      > 236 & 237 (busiest)
    o	Feb 2020 (pick up and drop off)
      > 161 & 237 (max duration)	[161: Manhattan (Midtown Center)]
      > 161 & 236 (busiest)
  -	Top busiest location:
    o	Feb 2020
      > Pick up hour (161, 237, 236)
      > Drop off hour (161, 237, 236)
    o	June 2020
      > Pick up hour (236, 237, 186)
      > Drop off hour (236, 237, 75)
  - Top Busiest routes:
    o	Feb 2020
      > 237-236
      > 236-236
    o	June 2020
      > 264-264
      > 237-236
    o	Note: Top 4 routes are similar for both months, the only difference is in the trip frequency of routes
