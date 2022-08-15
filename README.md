# surfs_up

# Overview
W. Avy liked the initial analysis, but he wants more information about temperature trends before opening the surf shop. Specifically, he wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.


## Resources
* Data Source: SurfsUp_challenge_starter_code.ipynb 
* Data File: hawaii.sqlite
* Software: Matplotlib, Python, Jupyter Notebook, Pandas, Numpy, Sqlalchemy


# Deliverable 1: Determine the Summary Statistics for June
Using Python, Pandas functions and methods, and SQLAlchemy, I filtered the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the month of June. I then converted those temperatures to a list, created a DataFrame from the list, and generated the summary statistics.

* Write a query that filters the date column from the Measurement table to retrieve all the temperatures for the month of June and convert the June temperatures to a list.


![June list](https://user-images.githubusercontent.com/106033535/184733718-d13a782b-278a-438a-bbc0-ea4047cc8dbe.png)


From the histogram, the temperature is frequently between 72 to 79 Fahrenheit.


<img width="431" alt="June graph" src="https://user-images.githubusercontent.com/106033535/184733841-1cad0510-db71-4e02-939c-3ab7c6caefce.png">


* Generate the summary statistics for the June temperatures DataFrame.


![June temps summary statistics](https://user-images.githubusercontent.com/106033535/184733979-f2bf3abe-0909-40ef-99ef-e8630dda4542.png)


# Deliverable 2: Determine the Summary Statistics for December
Using Python, Pandas functions and methods, and SQLAlchemy, I filtered the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the month of December. I then converted those temperatures to a list, created a DataFrame from the list, and generated the summary statistics.

* Write a query that filters the date column from the Measurement table to retrieve all the temperatures for the month of December and convert the June temperatures to a list.


![December list](https://user-images.githubusercontent.com/106033535/184734315-01b418bf-64b8-45da-b89f-5038cee33a8f.png)


From the histogram, the temperature is frequently between 66 to 75 Fahrenheit.


<img width="430" alt="December graph" src="https://user-images.githubusercontent.com/106033535/184734324-81f91024-3b2b-4a44-9fcb-fdadaafcbc5b.png">


* Generate the summary statistics for the June temperatures DataFrame.


![December temps summary statistics](https://user-images.githubusercontent.com/106033535/184734368-c4d5e5f7-64cc-4537-9e17-ebd24c028d7b.png)


# Summary
Based on the data analysis with the data provided the standard deviation is 3.25 in June and 3.75 in December, with a 0.5 difference in seasons. The maximum temperatures for June are 85 degrees and December is 83 degrees. With both seasons only ranging in a 2 degree difference, it is safe to say the location is optimal for sustainable year round profit. 
