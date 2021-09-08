### Project Proposal Template

#### Question/need:
* What is the framing question of your analysis, or the purpose of the model/system you plan to build? 

- WomenTechWomenYes holds an annual gala at the beginning of the summer each year. The organization has requested that the team utilizes the MTA subway data to help advise on the placement of their street teams for maximizing contact with commuters. The street steam will collect email addresses and those who sign up are sent fee tickets to the gala. The purpose of this outreach is to fill the gala event space with individuals passionate about increasing the participation of women in technology, and to concurrently build awareness and outreach

* Who benefits from exploring this question or building this model/system?

-Women who are interested in technology related careers would benefit most from the successful execution of this system. Maximizing the capacity of the event space with people committed to this mission will generate networking opportunities and new information that will hopefully jumpstart careers for women interested in this area. 

#### Data Description:
* What dataset(s) do you plan to use, and how will you obtain the data?

-I plan to use the MTA turnstile data from April, May, and June of 2021, the three months leading up to the event. The street team will be deployed during this time as people will more likely attend the event if it’s in the near future. 


* What is an individual sample/unit of analysis in this project? What characteristics/features do you expect to work with? 

-The train stations will be my primary unit of analysis.

* If modeling, what will you predict as your target?

#### Tools:
* How do you intend to meet the tools requirement of the project? 

-Ingest raw data into the DB browser for SQLite and queried from that database into Python via SQLAlchemy 
-Clean the data (removing nulls, rename columns) and add a datetime column using Python 
-Will be using MatPlotLib for the charts and SQLAlchemy for the dataframes:
	Create a histogram showing total traffic (entries/exits) for the top five stations
	Create histogram for total traffic for each datetime of the week
	Create line graph showing datetime, total traffic, and top 5 stations to see if the top five stations also happen to have the highest traffic on the 5 busiest days 

* Are you planning in advance to need or use additional tools beyond those required?

#### MVP Goal:
* What would a [minimum viable product (MVP)](./mvp.md) look like for this project?

-An MVP would include one or two of the graphs mentions above, along with my analysis of the findings. 
