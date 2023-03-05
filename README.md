# cyclistic-bike-share-analysis

## Introduction

Welcome to the Cyclistic bike-share analysis case study! In this case study, i will perform many real-world tasks of a junior
data analyst. In this study i work for a fictional company, Cyclistic, and meet different characters and team members. In order to
answer the key business questions, i would follow the steps of the data analysis process: ask, prepare, process, analyze,
share, and act.

## Scenario

Here i am a junior data analyst working in the marketing analyst team at Cyclistic, a bike-share company in Chicago. The director
of marketing believes the company’s future success depends on maximizing the number of annual memberships. Therefore,
my team wants to understand how casual riders and annual members use Cyclistic bikes differently. From these insights,
my team will design a new marketing strategy to convert casual riders into annual members. But first, Cyclistic executives
must approve our recommendations, so they must be backed up with compelling data insights and professional data
visualizations.


## Characters and teams

● Cyclistic: A bike-share program that features more than 5,800 bicycles and 600 docking stations. Cyclistic sets itself
apart by also offering reclining bikes, hand tricycles, and cargo bikes, making bike-share more inclusive to people with
disabilities and riders who can’t use a standard two-wheeled bike. The majority of riders opt for traditional bikes; about
8% of riders use the assistive options. Cyclistic users are more likely to ride for leisure, but about 30% use them to
commute to work each day.

● Lily Moreno: The director of marketing and my manager. Moreno is responsible for the development of campaigns
and initiatives to promote the bike-share program. These may include email, social media, and other channels.

● Cyclistic marketing analytics team: A team of data analysts who are responsible for collecting, analyzing, and
reporting data that helps guide Cyclistic marketing strategy. I joined this team six months ago and have been busy
learning about Cyclistic’s mission and business goals — as well as how i, as a junior data analyst, can help Cyclistic
achieve them.

● Cyclistic executive team: The notoriously detail-oriented executive team will decide whether to approve the
recommended marketing program.


## About the company

In 2016, Cyclistic launched a successful bike-share offering. Since then, the program has grown to a fleet of 5,824 bicycles that
are geotracked and locked into a network of 692 stations across Chicago. The bikes can be unlocked from one station and
returned to any other station in the system anytime.

Until now, Cyclistic’s marketing strategy relied on building general awareness and appealing to broad consumer segments.
One approach that helped make these things possible was the flexibility of its pricing plans: single-ride passes, full-day passes,
and annual memberships. Customers who purchase single-ride or full-day passes are referred to as casual riders. Customers
who purchase annual memberships are Cyclistic members.

Cyclistic’s finance analysts have concluded that annual members are much more profitable than casual riders. Although the
pricing flexibility helps Cyclistic attract more customers, Moreno believes that maximizing the number of annual members will
be key to future growth. Rather than creating a marketing campaign that targets all-new customers, Moreno believes there is a
very good chance to convert casual riders into members. She notes that casual riders are already aware of the Cyclistic
program and have chosen Cyclistic for their mobility needs.

Moreno has set a clear goal: Design marketing strategies aimed at converting casual riders into annual members. In order to
do that, however, the marketing analyst team needs to better understand how annual members and casual riders differ, why
casual riders would buy a membership, and how digital media could affect their marketing tactics. Moreno and her team are
interested in analyzing the Cyclistic historical bike trip data to identify trends.


## Ask

Three questions will guide the future marketing program:

1. How do annual members and casual riders use Cyclistic bikes differently?

2. Why would casual riders buy Cyclistic annual memberships?

3. How can Cyclistic use digital media to influence casual riders to become members?Moreno has assigned you the first question to answer: How do annual members and casual riders use Cyclistic bikes differently?


## Prepare

To prepare our data we have some fundamental questions that will guide us through the prepare process.

Guiding questions

1. Where is our data located?                                                                                                                                 
A- Our  data is located on a public server and is provided by Motivate International Inc. under license. 

2. How is the data organized?                                                                                                                                
A- The data is organized in a relational columns and rows table as a .CSV file format.

3. Are there issues with bias or credibility in this data? Does your data ROCCC?                                                                             
A- The data does follow ROCCC which is Reliable, Original, Comprehensive, Current, Cited. Since it is a public data taken from real world uses of a real        company. So the given data is reliable, original. And since the data contains every metric needed for a good data gathering operation it is comprehensive    as well. Also the data that is provided is of just past year it is current as well. Also since it is a public data it is cited as well. 

4. How are you addressing licensing, privacy, security, and accessibility?                                                                                   
A- The licensing for the data is provided since it is a public data. For the privacy all the personal identifications of the customer is removed so it          follows privacy concern well. Security aspect is cited since it is provided by a reliable source with citations. Accessibility is provided by the public      availability of the data.

5. How did you verify the data’s integrity?                                                                                                                   
A- The data's integrity is verified by looking at the citations and going through the data itself.

6. How does it help you answer your question?                                                                                                                 
A- The data has detailed observations of activities of the customers. And so it will be helpful to us to make good observations through data.

7. Are there any problems with the data?                                                                                                                     
A- There are some missing and duplicate data in the tables but it shouldn't be a problem in our analysis.


## Process

Now we have to process the data to clean, organize and process the data for analysis.

Guiding questions for our data processing.

1. What tools are you choosing and why?                                                                                                                        
A- Here for processing as well as for the other steps of our data analysis we are going to use Microsoft Excel.

2. Have you ensured your data’s integrity?                                                                                                                    
A- Yes i have ensured data's integrity. The data integrity has 3 aspects for it, being accuracy, completeness and consistency. The data is accurate since it is cited and made public. The data is also complete as it contains all the needed parameters for this analysis. it is also consistent since it is organized in a consistent format.

3. What steps have you taken to ensure that your data is clean?                                                                                               
A- I have checked for duplicates in data and found non. Also there are some nil data in tables but we can choose to ignore them since they would not be necessary for our analysis. Also since we are using MS-Excel, the original .CSV file from source is opened in excel. In the next step i have added two different columns in the table, one depicting ride length for every individual ride taken. Second column depicts the day of the week that the ride had occurred.

4. How can you verify that your data is clean and ready to analyze?                                                                                            
A- Since the data has been checked for duplicates and done some necessary calculations we can check and verify for it's organization for analysis step.
