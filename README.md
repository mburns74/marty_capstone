# marty_burns_capstone

Country Music Hall of Fame Capstone

Country Music Hall of Fame Capstone Website
Link: https://sites.google.com/view/country-music-capstone-mburns/home

Table of Contents

Website Link To Capstone Project
Motivation Behind Choosing This Topic
Questions
Collecting/Cleaning The Data
Challenges
Technologies Used
Sources
Conclusion


Website Link To Capstone Project:
Link: https://sites.google.com/view/country-music-capstone-mburns/home

Motivation:
I have a passion for country music. This passion comes from being raised in a musical family in the mountains of North Carolina and being exposed to country music at a very early age. My family's main source of entertainment for decades was the musical instruments they either made themselves or obtained by scraping together extra money from odd jobs and bartering. They took these instruments and came together on evenings and weekends in the kitchen/living room/front porch and performed their favorite country songs. Occasionally, they would have the luxury of visiting a neighbor who owned a radio that could pick up the signal of The Grand Ole Opry all the way from Nashville, TN. They instilled in me a love of country music as well as a great appreciation for its history and heritage. This led me to want to feature the Country Music Hall of Fame as my capstone project and see what digging into the actual data behind it would reveal.

Questions:
Which state has the most native Country Music Hall of Fame Members?
Into what home *state population ranges do Country Music Hall of Fame Members fall? Are more from very rural areas (less than 1 million) or more urban areas (more than 10 million)?? *State population in their year of birth
Which Country Music Hall of Fame Member came from the least populus state?
Within what decades were Country Music Hall of Fame Members born?
What period (years from birth to induction) did Country Music Hall of Fame Members have to wait for acknowledgement?
What is the gender breakdown among Members?
Are there Members with differences in ethnicity?
If scored in 4 areas of key career achievements (Grand Ole Opry Member, Star on the Hollywood Walk of Fame, Rock N Roll Hall of Fame Member, CMA Entertainer of the Year Award Winner), which Country Music Hall of Fame Member would be deemed as most successful? Have all 4 key achievements been achieved by any Member?
What percentage of Country Music Hall of Fame have achieved any of these 4 key achievements?
What is the distribution of Members among total key achievements?
Who is the most successful Country Music Hall of Fame Member?

Collecting/Cleaning Data:
The data I wanted to analyze had to be compiled through web scraping methods in python. This data was scattered in many different places on the web so I had to conduct scraping of more than one website in order to obtain the data I needed. I also had to clean the scraped data by removing unneeded information from the scraped tables, as well as performing datetime conversions and calculations. I then created multiple data frames and compiled them into one dataset for exploratory data analysis. In excel, I set up the dataset where I could leverage xlookups, countifs and advanced filtering functions to create the tables needed for my Tableau visualizations. I really enjoyed using the combination of multiple technologies to obtain, clean, analyze and build a story surrounding my data.

Challenges
It was a challenge to collect the data from so many different sources. The data collection alone through web scraping took a lot of time and effort that extended beyond classroom time and into weekends, late nights, and early mornings. Another challenge was laying out this data set in a way that would accommodate xlookups, countifs, and allow me to leverage tools within excel to build what would need to be fed into Tableau. Finally, determining what could be used as true measures of success was challenging. I initially thought I could use such data as population at the time of birth (rural vs urban), gender, ethnicity, etc. to measure success but in the end, those could not measure success. They did provide additional insights during the data analysis portion, so I included them in the capstone presentation as well. Building a custom website to present the capstone through was fun and a stretch as well.

Technologies Used
Python - for web scraping and collecting the data frames needed and also for cleaning of data
Excel - for building a custom combined dataset
Tableau - for creating visualizations
Google Sites - for capstone website creation
Git - for pushing python notebook to Github for version control

Data Sources

To answer the above questions, I used the following sources to collect datasets for my analysis:

Country Music Hall of Fame & Museum – https://www.countrymusichalloffame.org
The Grand Ole Opry - https://www.opry.com
Hollywood Walk of Fame - https://walkoffame.com
Rock & Roll Hall of Fame - https://www.rockhall.com
Country Music Association - https://www.cmaworld.com
Wikipedia - https://en.wikipedia.org
Population – https://www.macrotrends.net/states/arizona/population - **Data Source: U.S. Census Bureau - Population Estimates

Conclusion

In my quest to determine who is the most successful Country Music Hall of Fame Member, I gained so many insights into the country music genre and artists that I love so much. I did not realize that gender was so heavily weighted towards males. This really put into perspective for me the additional obstacles that females had/have to navigate to gain recognition in country music. I was also enlightened by the data that showed so many members of the Country Music Hall of Fame who had achieved NONE of the 4 key achievements measuring success in this capstone project. This highlighted the success measure and how diverse the two most successful members were in their navigation of Grand Ole Opry membership, their expansion into tv and film, their cross over out of the country genre and being recognized in the rock genre, as well as their accomplishment of being awarded CMA Entertainer of The Year. Through this project I have gained so much more respect for Country Music Hall of Fame members and their unique, diverse journey within their career. I can't wait to visit the Country Music Hall of Fame & Museum again with a whole new perspective and enlightenment that the data in this capstone brought to my attention.
 