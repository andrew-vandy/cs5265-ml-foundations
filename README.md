# CS5265 Foundations of Machine Learning

Customer churn is a major issue eCommerce businesses face. It is defined as the percentage of customers lost over a given period of time. According to customer data at Gorgias, repeat customers account only 21% of customers, but generate 44% of revenue and 46% of orders. Therefore, it has become increasingly important to identify and mitigate factors that cause customer churn.

According to customer churn analysis, decreasing monthly churn by just 5 customers (at a monthly contract size of $4,166) can save your business upwards of $250,000 a year. Market watcher Park Associates reports that Netflix lost about 9% of its subscriber base over a recent 12-month period compared with about 50% churn at Hulu. Acquiring new customers is far more expensive than retaining existing customers. It can cost up to 5 times more to acquire a new customer as it does to retain current ones.

## Performance Metrics

We will use the churn flag to indicate if a customer has churned or not. If we are predicting churn of a customer, for example, "1" would mean they have stopped purchasing products in the store and "0" would mean they continue to purchase products.

1. Confusion Matrix

  It illustrates classifier performance based on true positive (tp), true negative (tn), false positive (fp) and false negative (fn) predicted values vs actual values.
  
  * true positives (tp): We correctly predicted that there was churn
  * true negatives (tn): We correctly predicted there was no customer churn
  * false positives (fp): We predicted churn but in fact there was no churn
  * false negatives (fn): We predicted no churn but there was in fact customer churn
  
2. Accuracy

  It measures whether both positive and negative predictions were classified correctly. It indicates, how often is the classifier correct.

  Accuracy = (tp + tn) / (tp + fp + tn + fn)


 3. Precision

  It measures the fraction of true positive predictions from all the positive predictions. When we predict churn, how often did the classifier get it correct?

  Precision = tp / (tp + fp)
  
4. True Positive Rate ( aka Recall )

  It measures the fraction of true positive predictions from all positive observations. When there was actual churn, how often does the classifier predict it correctly?

  Recall = tp / (tp + fn)
  
5. F1 score

  This the harmonic mean of **Precision** and **Recall**

  F1 = 2 * ((Precision * Recall)/(Precision + Recall))
