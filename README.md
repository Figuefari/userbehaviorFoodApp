## Proyect description

Analysis of user behavior in a food product sales application.
To improve user engagement, some changes were proposed in the application and tested in an A/A/B test. We need to analyze the results and make a decision based on them.

## Tasks

1. Prepare the data for analysis.
2. Study and validate the data
   - Quantity and types of events
   - Average events per user
   - Data periods
3. Study of the event funnel
   - Event frequency
   - User proportions
   - Sequence of actions
   - User churn and retention
4. Study the experiment results
   - Users in each group
   - Proportion for the most popular event
   - Comparison of group results
   - Statistical hypotheses

## Data Description

Each record entry is a user action or event.

- EventName: event name.
- DeviceIDHash: unique user identifier.
- EventTimestamp: event time.
- ExpId: experiment number: 246 and 247 are control groups, 248 is the test group.

## Table of Contents

 1. Initialization:
    - Data Description
    - Data Loading
    - Preliminary Conclusions
    
 2. Data Preprocessing:
    - Duplicate Checking
    - Column Name Adjustment
    - EventName Adjustment and Verification
    - EventTimestamp Data Type
    - New Column for Date
    - ExpID Data Verification
    - Pre-analysis Data Processing Conclusions
 
 3. Data Analysis:
    - Question Formulation
    
    - Data Study and Verification
        - Event Quantity
        - User Quantity
        - Data Period
        - Old and New Records
        - Study and Verification Data Conclusions
        
    - Event Funnel Study
        - Frequency of Each Event
        - Unique Users Count per Event
        - Correct Event Sequence
        - Scenarios for Different Cases
        - Funnel Study Conclusions
    
    - Experiment Results Study
        - Users in Each Group
        - Control Groups 246 and 247 Study
        - Statistical Significance in the Most Popular Event
        - Statistical Significance for Other Events
        - Test Group 248 and Control Group 246
        - Test Group 248 and Control Group 247
        - Test Group 248 and Combined Control Groups
        - Summary of Test Analyses
        
        - Proportion Tests
        - Total Statistical Hypotheses and Significance Level

 4. Final Conclusions

## Used libraries

- pandas
- numpy
- matplotlib
- plotly
- scipy
