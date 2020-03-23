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