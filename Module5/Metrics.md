# Machine Learning Evaluation Metrics 

## Accuracy  
  Accuracy is simply (number right)/(number wrong)  

## Sensitivity and Specificity  
* Sensitivity  
  * If a person has diabetes how often will it be detected? (True positives) 
  * If 120 people have diabetes and 100 are detected Sensitivity is 100/120   
* Specificity  
  * If a person does not have diabetes how often will they test negative? (True negatives) 120 people do not have diabetes, 110 are labeled negative then sensitivity = 110/120.   
* What is the easiest way to get 100% Sensitivity  
* What is the easiest way to get 100% Specificity  

## Precision and Recall  

[see wikipedia](https://en.wikipedia.org/wiki/Precision_and_recall)  

### Precision  

"fraction of relevant instances among retrieved instances"

System identifies 100 cases of diabetes, 80 are truly diabetes, Precision = 80/100 = 0.8.  

### Recall  

"total amount of relevant instances that were actually retrieved"

120 cases of diabetes, system identifies 80, recall is 80/120 = .67.

Recall is the same as sensitivity. 

### Example  

The following Metrics were calculated from the KNIME "diabetesKNearestNeighbor" workflow.  


<img src="KNIMEMetrics.jpg" width="700">  

See this [notebook](https://github.com/bnorthan/inf-428-data-analytics-online/blob/master/python/notebooks/machine_learning/Metrics.ipynb) to learn how each metric was calculated   
