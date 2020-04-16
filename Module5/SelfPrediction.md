# Self Prediction  

## SELF PREDICTION VS TEST PREDICTION VS VALIDATION
* Self Prediction - make predictions on training data BAD
* Self Prediction - NO DON"T DO IT. STOP PLEASE NOW!!!!
* Test Prediction
* Run prediction on test set -- it may be BAD  

## Realy -- Self Prediction is very bad

* Run prediction on test set -- it may be BAD  
*  No problem you may have "Overfit" the training data  
   * Or maybe the patterns are not learnable... not every project works out  
*  Try different models and parameters until you get good test prediciton
*  Then do "Validation"  
   * Validition is when you test again on data you've never seen
* Needed because you may tuned your model to your test  
*
## CROSS VALIDATION
* Divides data into partitions  
* Tests on that partition, trains on rest of data  
* Advantage over partitioning  
* Each data point is predicted  
