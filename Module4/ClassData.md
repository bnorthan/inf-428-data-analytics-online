# Class Data  

This page will contain an evolving set of examples showing ways to clean and visualize the data INF 428/528 students will be using for their projects.  

## Adirondack Mountains  

This example shows how to clean data.  This data had many numerical fields that had extra characters in them, for examples '12 hours' and 4000' the extra characters made numerical analysis not possible.  Thus extensive cleaning was needed..  

[See here for the example notebook](https://github.com/bnorthan/inf-428-data-analytics-online/blob/master/python/notebooks/visualization_projects/mountains.ipynb)

[See here for video](https://www.youtube.com/watch?v=iHOgT2xMlTg)

In the example we needed to strip extraneous characters from the string.  

[see here for description of strip function](https://www.journaldev.com/23625/python-trim-string-rstrip-lstrip-strip)  

In the example we also used the 'apply' function to apply an operation to every row of a collumn.  

[see here for documentation on the apply function](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.apply.html)  

## Food Inspection data  

The dataset ```Food_Inspections.csv``` contains inspection info for over 200,000 inspections done at over 20000 restaurants.  This means that if we group the data there would be over 20000 groups... hard to visualize!

The goal of this notebook is to create a plot using only the largest groups of the dataset. This technique is useful when there are many small groups that we may not be interested in and want to see trends among the largest groups.  

[The notebook is here](https://github.com/bnorthan/inf-428-data-analytics-online/blob/master/python/notebooks/visualization_projects/Restaurant_Groups.ipynb)  

## Stocks (Apple vs Microsoft)

[This example](https://github.com/bnorthan/inf-428-data-analytics-online/blob/master/python/notebooks/visualization_projects/Stocks.ipynb) shows how to use a line plot to show the stock price of microsoft and apple over a number of years.  

