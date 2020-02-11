
### Open a CSV File in a Test Editor

https://www.howtogeek.com/348960/what-is-a-csv-file-and-how-do-i-open-it/

### Open a CSV File in KNIME 

[This Video may be helpful](https://www.youtube.com/watch?v=MN74H6MO5YE)

The example is on the KNIME Server under 'Introduction->OpenCSV'

We can open the file with only one node, the File Reader.  In this case it should already be configured, but when setting up for a new application you would need to configure it. 

1.  To configure, right click on the node and choose 'configure'
2.  To view the file table, right click on the node and choose 'File Table'

<img src="FileTable.jpg" width="800">    

### Open CSV in Python

[See this example](https://github.com/bnorthan/inf-428-data-analytics-online/blob/master/python/notebooks/introduction/OpenCSV.ipynb)  

We can use the Pandas libarary (which we will learn more about in Module 3) to open up a csv file with one line of code

``` python
import pandas as pd  
data=pd.read_csv('donuts.csv')  

# the head function display the first few lines of the data from the csv file  
data.head()  

```

