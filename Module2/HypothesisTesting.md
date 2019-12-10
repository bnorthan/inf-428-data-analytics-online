## Hypothesis Testing

Read [What is Hypothesis Testing](https://stattrek.com/hypothesis-test/hypothesis-testing.aspx)

## Null Hypothesis

The term "null hypothesis" usually refers to a general statement or default position that there is no relationship between two measured phenomena, or no difference among groups.  

This can be confusing to students as we ussually use statistical techniques to reject the null hypothesis.  So 

1.  The null hypothesis is no Difference between between groups.
2.  We often attempt to reject the null hypothesis. 
3.  If we reject the null hypothesis that means there is a difference between groups. 

## Null Hypothesis example

1.  We want to test a new drink that is suppose to improve a runner's 5k time. 
2.  We test two groups, one that consumes the drink, one that does not, then both groups run a 5k. 
3.  The null hypothesis is that there is no difference between the groups.  Their 5k times will be the same. 
4.  If we reject the null hypothesis then there is a difference between the groups and the drink did effect the runners 5k time. 


## P-Values

Read [538 Scientists explain p-values](https://fivethirtyeight.com/features/not-even-scientists-can-easily-explain-p-values/)  

The p-value is the probability of obtaining the observed sample results (or a more extreme result) when the null hypothesis is actually true.  

## Single Sample T-test

* T-value is calculated as follows  
<img src="T-tests.jpg" width="200">   
* then p is calculated from a table  
* [T-test table to determine p](https://www.sjsu.edu/faculty/gerstman/StatPrimer/t-table.pdf)  
* Read [Wikipedia Explanation](https://en.wikipedia.org/wiki/Student%27s_t-test#One-sample_t-test)  
* The single sample t-test tests the null hypothesis that the population mean is equal to a given number.

<script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
<script type="text/javascript"
            		src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML">
    		</script>
<h4>Single sample t-test</h4>
<ul>
	<li> $\overline{x}$ sample mean</li>
	<li>$\mu_0$ hypothesis mean</li>
	<li> Null hypothesis -> $\overline{x}=\mu_0$</li>
	<li> high P -> $\overline{x}$ more likely to be close to $\mu_0$,</li>
</ul>  

## INDEPENDENT (UNPAIRED) SAMPLES

* Tests if mean values are different between two samples
* Example: blood pressure between two groups (men and women)
* [Read Wikipedia Explanation](https://en.wikipedia.org/wiki/Student%27s_t-test#Independent_.28unpaired.29_samples) 

## PAIRED SAMPLES
* Tests if mean values are different when a group is tested twice  
* Example: blood pressure before and after a treatment
* [Read Wikipedia Explanation](https://en.wikipedia.org/wiki/Student%27s_t-test#Paired_samples)  









