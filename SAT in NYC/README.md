# SAT Scores in New York City

## Introduction
This project is focued on investigating the coorelations between SAT scores and demographics, race, gender and more in New York City. By focusing primarily on combining several messy data sets into a single clean one to make data exploration easier.

Here are the links to all of the data sets we'll be using:
- [SAT scores by school](https://data.cityofnewyork.us/Education/2012-SAT-Results/f9bf-2cp4) - SAT scores for each high school in New York City
- [School attendance](https://data.cityofnewyork.us/Education/2010-2011-School-Attendance-and-Enrollment-Statist/7z8d-msnt) - Attendance information for each school in New York City
- [Class size](https://data.cityofnewyork.us/Education/2010-2011-Class-Size-School-level-detail/urz7-pzb3) - Information on class size for each school
- [AP test results](https://data.cityofnewyork.us/Education/2010-AP-College-Board-School-Level-Results/itfs-ms3e) - Advanced Placement (AP) exam results for each high school (passing an optional AP exam in a particular subject can earn a student college credit in that subject)
- [Graduation outcomes](https://data.cityofnewyork.us/Education/2005-2010-Graduation-Outcomes-School-Level/vh2h-md7a) - The percentage of students who graduated, and other outcome information
- [Demographics](https://data.cityofnewyork.us/Education/2006-2012-School-Demographics-and-Accountability-S/ihfw-zy9j) - Demographic information for each school
- [School survey](https://data.cityofnewyork.us/Education/2010-2011-NYC-School-Survey/mnz3-dyi8) - Surveys of parents, teachers, and students at each school

All of these data sets are interrelated. We'll need to combine them into a single data set before we can find correlations.

Notice:
- The data sets include several different types of schools. So we need to clean them so that we can focus on high school only.
- Each school in New York City has a unique code called a `DBN`, or dirstrict borough number. This is very import information for data merging.
- Aggregating data by district will allow us to use the district mapping data to plot district-by-district differences.

From this project, I have learned:
- Handle files with different formats and columns
- Prepare to merge multiple files
- Use text processing to extract coordinates from a string
- Different types of merges
- How to handle missing values
- How to create school and district-level maps
- How to find correlations, and what those correlations mean

## Installation
- Install Basemap: `conda install basemap`
- You can view `SAT Scores in NYC.ipynb` directly on GitHub, or clone the repository and open on Jupyter Notebook.
