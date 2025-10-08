# MiniProject2
MiniProject2 - SQL: From Data to Insight

NYC Airbnb for STUDENTS 
StudentHub: NYC Rentals

Presented By: Kinga, Julia, Joma, Priyanka

Mini Project Overview:
Selecting NYC Dataset to analyse

1. Selecting NYC Dataset to analyse
    ●   Data retrieved from Kaggle
2. Tools chosen for analysis
    ●   SQL
    ●   Python
3. Database Design & Data Transformation
4. Cleaned & Filtered Script
5. Insights & Results

NYC Dataset selected - Data Acquisition, Transformation and Examination: 

A university ofﬁce is tasked with trying to ﬁnd the closest and most cost effective AirBnB in 
NYC for a group of students attending events in the city.

Topics covered:
★ Highlight the business problem and the hypotheses that guided our approach.
★ Highlight the primary sources of data and any complementary datasets.
★ Data acquisition, transformation and examination process
★ Discuss challenges faced during the data sourcing and integration.
★ Briefly describe how the supplemental data aligns with our primary dataset.

Database Design & Data Transformation:
StudentHub: NYC Rentals : Entity–Relationship Diagram (ERD) - project

<u>event</u>                     <u>studednt</u>                  <u>accomodation</u>         
■ event_id  INT ✅ PK   →→→→      ■ student_id  INT ✅ PK    ↑→→→→ ■ accomodation_id  INT ✅ PK
■ name  VARCHAR            ↓      ■ student_name    VARCHAR  ↑     ■ neighbourhood_group  VARCHAR
■ event_duration  INT      ↓      ■ accomodation_id INT →→→→→→     ■ room_type   INT
■ event_location  VARCHAR  ↓→→→→  ■ event_id  INT                  ■ price   INT
                                                                   ■ availability_365  INT

                                                             
