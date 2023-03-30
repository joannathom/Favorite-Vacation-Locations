# Favorite-Vacation-Locations
DATA INFORMATION ABOUT VARIOUS VACATION SPOTS

![Screenshot](IMG_15.png)

JUST LIKE THE GRISWALD's...we all need a vacation...

 The projects overall goal is to show the viewer what the best vacation locations are in the United States. The data will show the top places based on the amount of visitors, location, and cost of each trip. The visuals will show the top rated places in the United States to visit. It will also show the data from greatest to least places to visit based on tourist numbers. But this could be a great resource for people who like areas with less traffic and tourist numbers. But then it could be a great resource for people who love the big crowds and the energy. 
These websites and sources are credited with the research and data for my project: 
* Credit given to sources Web link: https://www.getyourguide.com/country-l168990/day-trips-tc172?p=3&sort=popularity&order&searchContext=TRIP_ITEM_GROUP&collectionId=172&tcId=172
* CSV file from https://www.downloadexcelfiles.com/us_en/list-top-tourist-places-us#.ZBaO_HbMK5c&gsc.tab=0

# Requirements to Run the Program:
* Open file Final-Project.ipynb
Before you do any of the below please activate your terminal to be in a virtual enviroment:
 * `python -m venv venv`for Windows 
 * `Source venv/scripts/activate` for Windows Computers
 * `python3 -m venv venv`for Macs 
 * `Source venv/bin/activate for` for Mac Computers

Use this code to  set up the requirements file:
* `pip freeze > requirements.txt`
* `pip install -r requirements.txt`

Use these steps to save changes to the github repository:
* git add <file>
* git commit -m '<file>'
* git push 
* refresh repository to view changes online

Then to explore and analyze the data you will need to install these libraries listed in requirement.txt these below:
* import pandas as pd 
* import numpy as np
* import pathlib  
* import matplotlib 

To work with python data you will need to install these: 
* Gitbash or a Shell Terminal
* Pandas as pd
* Python 3.11 
* Jupyter Notebook 
* Visual Studio 

# Features:

## Feature 1: Exploring the Data 
    Used pandas to view the data in charts that pull each column.
    Created a repository in Github or fork existing repository.
    Researched and downloaded a CSV data file to the github repository.
    Juypter Notebooks will also need to be installed for a notebook and opened while using Visual Studio.
* ReadIn Data: Reading data from a CSV file. 
## Feature 2: Cleaning the Data 
     Cleaned data by adding a column and title, pulling out nun values.  
## Feature 3: Analyzing the Data 
     The charts were created using python code/Jupyter notebooks to show information. 
     The data with Matplotlib to create a line chart, bar graph, and pie chart for percentanges. 
### * Questions and Visualizations 
     These were created with matplotlib to show the data analysis below.


## Feature 4:  Visualizations/Questions
# Questions 

* Which vacation location had the most visitors and the least visitors?
* What is the visual percentage difference of the top 6 places to visit on vacation?

## Create a line graph to show greatest to least on tourist populations each year
`Vacation_df.plot(title = 'Favorite-Vacation-Locations', x = 'Place', xlabel = "Location", rot = 90)`

## Plot a bar graph to show location to visitor ratio.
`Vacation_df.plot.bar(title = "Favorite-Vacation-Locations", x = "Place", xlabel = "Locations", rot = 90, ylabel = "Vistiors(millions)")`

## Plot a pie chart for percentages. 
## Import libraries
* from matplotlib 
* import pyplot as plt
* import numpy as pd

## Creating dataset
`Place = ['Walt Disney World Resort', 'Mall of America', 'Time Square', 'Las Vegas Strip','National Mall and Memorial Parks', 'Disneyland Resort',]`
 
`Visitors_millions = [45,40,35,31,24,22.10]`

## Creating plot
`fig = plt.figure(figsize =(10, 7))`
`plt.pie(Visitors_millions, labels = Place, autopct='%1.0f%%')`

## show plot
`plt.show`

## Feature 5: Interpret Data and Graphical Output 

Throughout the project in 'Final-Project.ipynb' I have # explaining the process with each code and then the reason for the output.The first step is to research the data and pull a csv to download with data and numbers to show the project set numbers, exploration of data, clean data adding or pulling columns, numbers not needed in the data set, and then of course plotting the data in line graphs, bar graphs, and pie chart plot so that the viewer better understands what the analysis is trying to show them. 
