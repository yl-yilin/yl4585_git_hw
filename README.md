# IEOR E4501 Final Project 
# Squirrel Tracker: A Visualization Web Application for Tracking Squirrels 
## Background 
This is a web appllication project developed with Django, a tool in python, that allow us keep track of all known squirrels. We used a dataset from the **2018 Central Park Squirrel Census**, and visualized the sightings of squirrels by adding, updating, viewing, and analyzing the squirrel data.  

## Dataset
In the project, we import [2018 Central Park Squirrel Census](https://data.cityofnewyork.us/Environment/2018-Central-Park-Squirrel-Census-Squirrel-Data/vfnx-vebw) dataset. This is a csv file that included 3024 sightings and 30 variables such as ID, date, age, shift, and so on. 

## Prerequisites
Using Python 3.6+, and undering Django web framwork and Git version control.

## Management Commands 
**Import:** A command that can import dataset from a csv file called 2018 Central Park Squirrel Census. The path should be located after the management commmands in the command line as below.

```sh
python manage.py import_data/path/to/2018-Central-Park-Squirrel-Census.csv
```
