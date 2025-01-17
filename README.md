# Gdriveplotter

## Introduction
This is a basic project built to read google sheet from google drive using the google credentials and google sheet key. The library can plot 2 types of graphs i.e. line plot and scatter plot.


## Files
**README.md**  -> File describing the project  
**setup.py** ->setup file to create a Python Library and host it on PyPi  
**test.py** ->test file to check if the program is working or not  

## Gdriveplotter
**__init__.py**  -> file where the program is implemented
**Screenshots**  -> Added screenshots of the working library

## Getting Started
The user will have to login to the below link.
```bash
    https://console.developers.google.com
 ```
    
After which the user has to do the following:
1. Create a new project
2. Add Google Drive API and Gsheet API
3. Go to Credentials and create a Service account
4. Get the key by downloading the json file
5. Use this file as Credentials for using the library



## __init__.py file
This file contains a function named **gdplot()**. The library is built to ask the user to enter their credentials and Gsheet key to read the gsheet. The function will print out the head of the dataframe using pandas. Another input is taken from the user to mention the type of graph required i.e. Line plot or Scatter plot. After which the user has to mention the x-axis column name and y-axis column name and the function plots out the required graph.


## Creating Python Library and Publishing on PyPI
Here is the link which will help you to create python library and publishing it on PyPI
```bash
    https://medium.com/little-big-engineering/lets-talk-about-python-packaging-6d84b81f1bb5
```

## Installing the Library from PyPI
pip install gdriveplotter

## Importing and calling the function
```bash
    import gdriveplotter
    gdriveplotter.gdplot()

```

## Pypi Link
```bash
    https://pypi.org/project/gdriveplotter/
```

## Note
The file should be in gsheet format to work. It wont work for any other format.
