Assignment 2 - 14 points

Due February 16th

Submission - Submit a word document through Blackboard which contains answers to the assignment questions, and your KNIME workflow files, and IPython nobebook files. See detailed instructions from Assignment 1 [here] that explain how to .zip these files and submit via blackboard.     

HINTS:    

Look at notebook Ind. T-Test Baseball Teams.ipynb (notebooks/statistics) and KNIME workflow ‘Statistics’ to see examples that are relevant. 

Read this experiment on [Muscle Metabolism](http://learntech.uwe.ac.uk/da/Default.aspx?pageid=1438)  

The above link summarizes "A study of the effect of caffeine on muscle metabolism".  You will attempt to reproduce their results in both KNIME and IPython notebook. You sill submit a word document in blackboard.  

You will have to perform steps 1 through 5 in both KNIME and in IPython notebook

1.  Explain what a ‘single sample t-test’ and a ‘independent samples t-test’ are, give an example application for each, and explain the differences.  (submit written answer in word document)
1.  Transfer 'Placebo vs. Caffeine' data table to .csv format (hint, copy and paste into text editor or spreadsheet (may need minor formatting)) (no need to submit, but you will need this data for the remainder of the assignment) 
2.  In KNIME and IPython Calculate simple stats (mean, min, max, std) take screen shots of your work and submit in the document. 
3. In KNIME and IPython produce Histograms both of the placebo and Caffeine groups. Submit a screentshot. 
4.  Perform an independent samples t-test between the Placebo and Caffeine groups in both KNIME and IPython. (submit a screenshot)
 5.  Do the results agree with the results of the original [experiment](http://learntech.uwe.ac.uk/da/Default.aspx?pageid=1438)?? (they should, if not trouble shoot what is happening)
6.  What is a normal distribution? (submit a written answer)


7.   Research how to calculate confidence intervals of a mean value assuming a normal distribution using Python and R (should be able to do it in 1 line of code).  Show the line of code in each language (just copy the code into the word document) and talk about how they are the same and different. 
8.  What does the example notebook in the github repository called ‘python/notebooks/statistics/NormalDistributionAndConfidenceIntervals’ do?? (submit a written answer)
9.  How does changing the standard deviation (std) defined in block 2 affect the histogram and the confidence interval of the data and of the mean?? (try a few different values and take a screen shot)
9.  How does changing the number of samples change both of the above??  
10. Explain the difference between standard deviation and standard error.  Why is standard error important??  (submit a written answer)