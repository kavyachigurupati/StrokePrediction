# Stroke Prediction Conclusion

**Q: Do I need to distribute file `README.md` and/or `LICENSE.md`?**

**A:** No. The header `acutest.h` includes URL to our repo, copyright note and
the MIT license terms inside of it. As long as you leave those intact, we are
completely fine if you only add the header into your project. After all,
the simple use and all-in-one-header nature of it is our primary aim.


**Q: What was unique about the data ?**

**A:** The features was multi variant and it had many features for which we applied label encoding. The data was biased because it tried to predict people did not get stroke

**Q: Did you have to deal with imbalance ?**

**A:** Yes, We did under sampling but model was over fitting so we shifted to over sampling and weight balancing

**Q: What data cleaning did you do ?**

**A:** We handled missing and NaN values and unknown values.

**Q: Did we do Outliner treatment ?**

**A:** We did outlier treatment for BMI because there were few values above 60 and the count was insignificant.
We also removed one data entry for gender where it said Other.

**Q: Did you create any new additional features / variables ?**

**A:** We did not add any additional features but we did oversampling to make the model biased.

**Q: What was the process you used for evaluation?  What was the best result ?**

**A:** We are computing accurace, precision and recall and we will display the confusion matrix.

**Q: What were the problems you faced? How did you solve them ?**

**A:** Initially the data was imbalanced so we fixed that with data undersampling and then the data was very less and model was overfitting so we did oversampling to fix that. We also tried various methods for supervision models.

**Q: What future work would you like to do ?**

**A:** The accuracy for train for 95%  and test was 90%. We would like to improve the accuracy using neural network. Currently, the data set is limited so we did not include neural network, but out future goal is to improve the data and add neural network.
