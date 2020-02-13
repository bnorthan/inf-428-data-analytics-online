## Groups and Aggregation

### What is groupby ??

Group by is used to split and aggregate data based on some criteria.  The Groupby command is available in all data processing frameworks, it is also available in SQL.  

### Python Groupby
[Class Groupby Example](https://github.com/bnorthan/inf-428-data-analytics-online/blob/master/python/notebooks/data_wrangling/Groupby.ipynb)

[Pandas Groupby](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.groupby.html)

### KNIME Groupby

[KNIME Groupby](https://www.youtube.com/watch?v=JQ-OWMt48ew)

See the class KNIME groupby example (under Data_Wrangling->Groupby) 

To use groupby first search for the groupby node, import it into a project and choose the group column. In this case we choose to group baseball stats by year.  (The file that has been loaded in this example, contains baseball stats, for every player for every year in baseball history.)    

<img src="KNIMEGroups.jpg" width="700">  

Next we need to choose the aggregation column and aggregation type.  The aggregation column should be a numeric column that we wish to firther analyze.  The aggregation type specifies how we summarize the data.  In this case we choose sum.  The result is that we generate a new table that contains the sum of all the homeruns hit by all players over each year.  

<img src="KNIMEAggregate.jpg" width="700">  

