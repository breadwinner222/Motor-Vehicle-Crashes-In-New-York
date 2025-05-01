# Motor-Vehicle-Crashes-In-New-York

# Team Name:
Group 9
# Team Members:
1. Colin Maguire @Maguireoooo
2. Aidan Brown @breadwinner222
3. Will Shimmons @WillShimmons
4. Sidhant Arora @SidhantArora4610
   
# Dataset Description and Overview:
The dataset we used was found on the public website data.gov, titled: Motor Vehicle Collisions – Crashes (New York City)
This data contains motorvehicle crashes that were reported from 1998 to 2025 in different areas of New York City. It contains 2,169,687 rows and 30 columns making it a large and rich dataset full of varied categorical and quantitive data. 
Before going in depth with this data, we must first understand the different variables that we analyzed. 
We first began with the categorical set: 
* Borough (which town the crash happened in)
* Type of Vehicle (sedan, SUV, taxi, or for-hire vehicle like Uber/Lyft)
* Cause of Crash (texting, speeding, weather, under the influence, etc.)
* Time of Day (morning, afternoon, evening, night)

Then with the quantitative set: 
* Fatality Rate 
* Number of Crashes
* Number of Pedestrian Injuries

This detailed dataset allowed us to gain a hold of both WHERE and WHY accidents happen. Along with this, we attempted to determine which vehicle types and locations are most dangerous for pedestrians across New York City.


# Project Questions:
Question 1: How do the time of day and boroughs of New York City affect the fatality rate from car crashes?

* This question is important because it connects human behavior, their driving patterns throughout the day, and urban structure of different boroughs, or towns to prepare safety outcomes. By understanding when and where fatal crashes are most likely to occur, city officials can better plan traffic interventions, set rush-hour policies, and focus infrastructure funding to save lives. The question ties directly to the dataset through time variables (Crash Time) and location variables (Borough).

Question 2: Which types of vehicles are most often involved in crashes that lead to pedestrian injuries, and where do these crashes happen more frequently?

* This question now, sounds a bit different in the way it's worded, however it is just as important because it helps us analyze the safety of pedestrians in the crowded city, which also turns out to be a social issue. It's important economically and culturally as well because it affects where people feel safe walking, also affecting how insurance and healthcare costs rise, and how transportation services like Uber and Lyft interact with the public and New York City's residents. Our dataset directly supports this question with vehicle type data and pedestrian injury numbers, helping identify the most dangerous vehicle categories and the boroughs or ZIP codes where injuries cluster.

There are many reasons why these two questions are important and serve a key factor in showing us data and results on where and why accidents happen around New York City, however the main answer it gives us is how to improve the public safety and enhance awareness, saving more lives and reducing fatality. Through these two questions, we can analyze the most frequent areas and rush hours where response can be quicker and a better structure can be placed to navigate the drivers and pedestrians towards safety.

# Dataset Manipulations:
To prepare the data for analysis in Tableau, several manipulations were necessary, just a few changes at least. First, we created a calculated field for Time of Day by grouping crash times into Morning, Afternoon, Evening, and Night, since the raw dataset we got from the website only gave us crash timestamps. We also filtered out NULL values for boroughs and vehicle types to make the graphs cleaner and avoid empty or incorrect data points. In the pedestrian injury analysis, we filtered the vehicle type column down to the top 6 most common vehicles, removing some labels and combining duplicates, so the heat map would clearly reflect the most impactful vehicle groups. For both graphs, we used stepped color scales to highlight intensity differences in fatalities and injuries, making the visuals easier to interpret. As you can see, the manipulations were slightly different for each question of course. In summarization, For Question 1 (fatality rates by borough and time), we mainly focused on creating the Time of Day field, removing NULLs for boroughs, and sorting the data by boroughs to clearly show where fatalities happened the most. For Question 2 (pedestrian injuries by vehicle type), we mainly worked on filtering and cleaning the vehicle types, choosing the top 6 vehicles, and turning the graph into a heat map to easily show where the injuries were happening most often.

In the end, these added changes, or also better known as manipulations made our lives easier and the data much cleaner to work with. It also helped us find better answers for our questions, and without the dataset manipulations, our data would've been messier and difficult to work with, making it confusing to analyze and depict results.


# Analysis & Results:
In Question 1, our group learned that most fatal car crashes happen mid-day, which is not surprising as that is when the traffic is heaviest during rush hour, people are coming home from work or school and may be distracted and tired. Brooklyn saw the highest fatalities across all of the boroughs and probably because it is such a densely populated location with a plethora of residential avenues where mishaps are likely to happen. That suggests some place and some point in the day would see merit in increased precautions, including lessened speed limitations, better crosswalks, or enhanced traffic signs to curb accidents and avoid loss of life. Our visualization made it simple to see which boroughs and times were most vulnerable. 

For Question 2, based on our heat map, Queens, Brooklyn, and the Bronx were the locations where most of the pedestrian crashes from car accidents took place. The most active cars were sedans and SUVs, but for-hire vehicles like taxi and Uber, Lyft were involved in many of these crashes as well. This translates to additional regulations for drivers of ridesharing and better protection for individuals walking through traffic-congested areas. Easy identification of the riskiest areas pedestrians walk through with Tableau gave us good ideas about where the city can add more safety precautions to make New York City a safer place for everyone. The areas with the darkest colors represent where the most injuries occur, which can be seen most prevalent and powerful in Queens and Brooklyn, followed by the Bronx. This indicates a less safe area and could be taken into consideration for any future residents of these areas.

Overall, through organizing, manipulating, and cleaning up the data, we were capable of finding noticeable trends that we needed about where and when most dangerous and deadly crashes occurred within New York City. Through focus on quantitative data like injury rate and number of crashes to show the most dangerous areas for pedestrians in this graph. You would be able to take these data points and become a little more informed on the safe vs unsafe areas to live in NYC to be able to make better decisions on where to live. Our plots (shown below) made it visually simple for us to notice which most dangerous boroughs, hour of day, and vehicles had been involved with ease. We can use our findings to help city officials to better decide upon areas to increase roads and to better protect pedestrians. In the years to come, even more accurate information could make New York City even safer for everyone.

<img width="792" alt="Question 1 Graph" src="https://github.com/user-attachments/assets/d44bfcf2-aa9d-4e83-9bd8-e68426c59926" /> <img width="792" alt="Question 2 Graph" src="https://github.com/user-attachments/assets/926abdfd-b475-47ef-a9ea-9264b29021bc" />


# Tableau Packaged Workbook:


