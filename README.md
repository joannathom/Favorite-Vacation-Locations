# Favorite-Vacation-Locations
Data Information About Various Vacation Locations


## Just Like the Griswald's we all want a vacation at some point in the year....
# Project Objective:
This is a final project for Code Kentucky to demonstrate what we have learned throughout the Data Analyst Part 1 section. The projects overall goal is to show the viewer what the best vacation locations are in the United States. The data will show the top places based on the amount of visitors, location, and cost of each trip. The visuals will show the top rated places in the United States to visit. 
These websites and sources are credited with the research and data for my project: 
* Credit given to sources Web link: https://www.getyourguide.com/country-l168990/day-trips-tc172?p=3&sort=popularity&order&searchContext=TRIP_ITEM_GROUP&collectionId=172&tcId=172
* CSV file from https://www.downloadexcelfiles.com/us_en/list-top-tourist-places-us#.ZBaO_HbMK5c&gsc.tab=0

# Requirements:
Before you do any of the below please activate your terminal to be in a virtual enviroment:
 * 'python -m venv venv'
 * 'Source venv/scripts/activate' for Windows Computers

Use this code to  set up the requirements file:
* 'pip freeze > requirements.txt'
* 'pip install -r requirements.txt'

Then to explore and analyze the data you will need to install these libraries listed in requirement.txt these below:
* import pandas as pd 
* import numpy as np
* import pathlib  
* import matplotlib 

To work with python data you will need to install these: 
* Python 3.11 
* Jupyter Notebook 
* Pandas 
* Matplob lib 
* Pathlib
* Visual Studio 

# Features
* Created a repository in Github or fork existing repository.
* Research and download a CVS data file to the github repository.
* Juypter Notebooks will also need to be installed for a notebook and opened while using Visual Studio.
  ## Skills Developed
* Reading data from a CSV file.
* Exploring the Data with pandas to view the data in charts that pull each column.
* Cleaning the Data adding a column and title, pulling out nun values.  
* Analyzing the Data with Matplotlib to create a line chart, bar graph, and pie chart for percentanges. 


# Questions 

* Which vacation location had the most visitors and the least visitors?
* What is the visual percentage difference of the top 6 places to visit on vacation?
# Visualizations 
   ## Created a line graph to show greatest to least on tourist populations each year
'Vacation_df.plot(title = 'Favorite-Vacation-Locations', x = 'Place', xlabel = "Location", rot = 90)'
# Plot a bar graph to show location to visitor ratio.
'Vacation_df.plot.bar(title = "Favorite-Vacation-Locations", x = "Place", xlabel = "Locations", rot = 90, ylabel = "Vistiors(millions)")'

# Plot a pie chart for percentages. 
## Import libraries
from matplotlib import pyplot as plt
import numpy as pd

## Creating dataset
'Place = ['Walt Disney World Resort', 'Mall of America', 'Time Square', 'Las Vegas Strip','National Mall and Memorial Parks', 'Disneyland Resort',]'
 
'Visitors_millions = [45,40,35,31,24,22.10]'

## Creating plot
'fig = plt.figure(figsize =(10, 7))'
'plt.pie(Visitors_millions, labels = Place, autopct='%1.0f%%')'

## show plot
'plt.show'