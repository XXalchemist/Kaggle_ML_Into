# Classification ML Algo's

## Content

|**Sr. No.**| **Algorithm Name**|
|---|---|
|1.| Logistic Regression|
|2.| SVM |
|3.| Decision Tree |
|4.| Random Forest|
|5.| Naive Baye's|
|6.| KNN |

## Classification Template

1. Import Libraries
2. Split Dataset
3. Feature Scaling
4. Create Classifier
5. Predict
6. Make Confusion Matrix
7. Visualizing the result
   
# Algorithm's

## Logistic Regression 

- Used to predict probability.touch
- Statistical math model to create a binary depedent classifier.
- Linear regression + Sigmoid Function ( 1/(1+e^-y) ) = Logistic Regression ( ln(p/1-p) = b0 + b1 * x )

## SVM

- Support Vector Machine
- Sees boundary points rather than most frequent points

## Kernel SVM

- SVM having different kernels.
- used when data is not linearly depedent.
- Types of kernel :- Gaussian RBF kernel, Sigmoid Kernel, Polynmial Kernel
  
## Decision Tree

- Classifier can be used :- Gradient Boosting, Random Forest
- Tree created to classify

## Random Forest

- Collection of multiple decision trees
- Uses **Ensemble Learning( multiple ml algo's combine altogether )**

### Steps

1. Pick at random K datapoints from the traaining set
2. Build the decision tree associated to these K datapoints
3. Choose the nnumber N tree of trres you want to build and repeat step-1 and step-2
4. For a new data point, make each one of your Ntree predict the category to which the datapoints belongs and assign the new datapoint to the category that wins the majority vote.



