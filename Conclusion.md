# Stroke Prediction Conclusion

**Q: What was unique about the data ?**

**A:** The features were multi-variant and it had many features for which we applied label encoding. The data was biased because it tried to predict people did not get stroke

**Q: Did you have to deal with imbalance ?**

**A:** Yes, We did under-sampling but model was overfitting so we shifted to oversampling and weight balancing

**Q: What data cleaning did you do ?**

**A:** We handled missing and NaN values and unknown values.

**Q: Did we do Outliner treatment ?**

**A:** We did outlier treatment for BMI because there were few values above 60 and the count was insignificant.
We also removed one data entry for gender where it said Other.

**Q: Did you create any new additional features/variables ?**

**A:** We did not add any additional features but we did oversample to make the model biased.

**Q: What was the process you used for evaluation?  What was the best result ?**

**A:** We are computing accuracy, precision, and recall and we will display the confusion matrix.

**Q: What were the problems you faced? How did you solve them ?**

**A:** Initially the data was imbalanced so we fixed that with data undersampling and then the data was very less and the model was overfitting so we did oversampling to fix that. We also tried various methods for supervision models.

**Q: What future work would you like to do ?**

**A:** The accuracy for the train for 95%  and the test was 90%. We would like to improve the accuracy using a neural network. Currently, the data set is limited so we did not include a neural network, but our future goal is to improve the data and add a neural network.