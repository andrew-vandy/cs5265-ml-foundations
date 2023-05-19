# CS5265 Foundations of Machine Learning

Customer churn is a major issue eCommerce businesses face. It is defined as the percentage of customers lost over a given period of time. According to customer data at Gorgias, repeat customers account only 21% of customers, but generate 44% of revenue and 46% of orders. Therefore it has become increasingly important to identify and mitigate factors that cause customer churn.

## Performance Metrics

1. Confusion Matrix

  Presents the true positive (tp), true negative (tn), false positive (fp) and false negative (fn) predictions. 

2. Accuracy

  It measures whether both positive and negative predictions were classified correctly.

  Accuracy = (tp + tn) / (tp + fp + tn + fn)


 3. Precision

  It measures the fraction of true positive predictions from all the positive predictions

  Precision = tp / (tp + fp)
  
4. True Positive Rate ( aka Recall )

  It measures the fraction of true positive predictions from all positive observations

  Recall = tp / (tp + fn)
  
5. F1 score

  This the harmonic mean of **Precision** and **Recall**

  F1 = 2 * ((Precision * Recall)/(Precision + Recall))
