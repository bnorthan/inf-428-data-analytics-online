## PANDAS  

Pandas is a data analysis library for Python.  It offers functions and structures for dealing with numerical data tables and series.  The most important data structure in Pandas is the DataFrame.  A DataFrame can be created from a csv file with one line of code

``` python
import pandas as pd
myDataFrame = pd.read_csv("myfile.csv")
```

A dataframe is

* Two dimensionsal data structure  
* sort of like a spread sheet  
* sort of like a relational database  

## Key Concepts

Key concepts of Pandas are below.  You should learn these concepts by working through the [Class Pandas Notebook](https://github.com/bnorthan/inf-428-data-analytics-online/blob/master/python/notebooks/data_wrangling/Pandas.ipynb) and other tutorials (such as [this one](https://www.learndatasci.com/tutorials/python-pandas-tutorial-complete-introduction-for-beginners/))  
* use ```import pandas as pd``` to get access to Pandas (pd is like a shortcut)
* use ```df=read_csv('file name')``` to open the file  
* use ```print(df.shape)``` to see size of data  
* use ```print ("columns: ",df.columns``` to see the headers describing data categories  
* use ```print ("index: ",df.index)``` to see the index that is used to reference data rows  
* use ```df.values``` to get data as numpy array  
* series -> each column of dataframe is a series  

## Work through

[Class Pandas notebook](https://github.com/bnorthan/inf-428-data-analytics-online/blob/master/python/notebooks/data_wrangling/Pandas.ipynb)  


[Another Pandas Tutorial](https://www.learndatasci.com/tutorials/python-pandas-tutorial-complete-introduction-for-beginners/)  

There are many more ...  feel to google for one that works for you.   

As always... if you are confused about anything  ask on the class message boards.