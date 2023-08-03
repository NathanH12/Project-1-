# Project-1-
The aim of our project is to perform an in-depth analysis of the Olympics dataset to gain valuable insights into the history and trends of the Olympic Games. We are particularly interested in exploring the relationship between an athlete's attributes and their performance in the Olympics.

We will be using the Olympics dataset obtained from Kaggle, which includes information such as athlete details (ID, Name, Sex, Age, Height, Weight), team information (Team, NOC), Games details (Year, Season, City), sports information (Sport, Event), and medal achievements (Medal type). 

In the question “How has the average age of Olympic athletes changed over the years?” The csv file was first organized into a main data frame using pandas, from there the data was sorted by gender by grouping the data frame by “sex” and “age”. Once the data was divided by gender, separate data frames were created for each gender. Once the data was separated into gender data frames, matplotlib was used to create graphs that show the average age of gender per year. Then to find the oldest and youngest participants of each gender the max and min functions were used as well as sorting the data frame by ascending and descending order.

On the third part of our analysis, we performed an exploratory analysis on participating countries, we looked at the top ten participating countries. We also investigated male and female count and their ratios.
The table below contains the top ten countries with their respective players.
COUNTRY	       NUMBER OF PLAYERS
United States	    4979
France	          4608
Italy	            4023
Great Britain	    3282
Canada	          2536
Australia	        2235
Sweden 	          2057
Germany	          1965
Spain	            1836
Switzerland	      1560
	

Conclusions:
	Seven out of the top ten participating countries are from Europe.
	United States, Australia, and Canada are the three countries outside Europe.
	We could infer that European countries are dominant in the Olympics games.

Ratio of male to Female Players
	The male to female count is 51,800 and 18,200 respectively.
	Male to female ratio is 74:25.
	We could infer that the Olympic games is a male dominated event.

Summary statistics and data Description 
Source	Kaggle
Variables	Name, sex, age, height, weight, team, noc, games, year, season, city, sport, event and medal
Number of Variables	    14
Number of Observations	70000
Mean Age	              24.64
Mean height	            134.75
Mean weight	            53.57
Maximum Age	            88
Maximum height 	        223
Maximum Weight	        214
Number of male participants	51,800
Number female participant	18,200
Shortest athlete	127 cm
Tallest athlete	223 cm
Lightest athlete	25 Kg
heaviest	214 Kg

