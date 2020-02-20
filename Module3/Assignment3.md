Individual Assignment: 14 Points
 
Purpose of assignment: 

Learn to join datasets
Learn to create groups
Learn to analyze groups for trends
Learn to plot data from groups

Background

Two years ago NIKE introduced a new shoe called the 4%, that was advertised as improving running times by 4%.  Very quickly almost all elite athletes began using the new shoe.  In this assignment you will look at data from 2014 and 2015 (before the new shoe waas introduced) and 2018 and 2019 (at which point the majority of athletes were using the new shoe).  

You will group this data in an attempt to identify how running times changed for elite athletes after the introduction of the new shoe. 

You will need the following datasets, men2014.txt, men2015.txt, men2018.txt, mean2019.txt, women2014.txt, women2015.txt, women2018.txt, and women2019.txt.  

The datasets can be found on github here  

https://github.com/bnorthan/inf-428-data-analytics-online/blob/master/python/notebooks/data_wrangling/

You will use the following notebook as a reference  

https://github.com/bnorthan/inf-428-data-analytics-online/blob/master/python/notebooks/data_wrangling/MarathonShoes.ipynb  

Answer the following questions in a word document and submit on BlackBoard  

1.  In the example we use ```pd.read_fwf``` to open data.  What is the ```pd.read_fwf``` function??  Why do we use it in this case instead of ```pd.read_csv```??  
2.  What do we pass an extra parameter called ```name``` (hint for help on the ```pd.read_fwf``` function call ```help(pd.read_fwf```)  
3.  Why do we call ```.head(numRunnersToAnalyze()``` at the end of each ```read_fwf``` call??  (hint try changing the parameter numRunnersToAnalyze to 10 and rerun the notebook)
4.  Modify the notebook so that we also read the men and women datasets from 2013 and 2018 (hint you will have to copy and paste a bit).  Run the notebook over and take a screen shot.  
5.  Change the ```numRunnersToAnalyze``` parameter to 10 and rerun the notebook.  Take a screen shot.  Are the trends in performance for the top 10 different than the top 100??  
6.  Output the ```final``` dataframe to a csv file and import it into KNIME (take a screen shot)  
7.  Rerun the groupby operation in KNIME (take a screen shot) 
8.  In Python and KNIME make a barplot showing the average time of each runner.  