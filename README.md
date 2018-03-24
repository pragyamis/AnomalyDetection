# AnomalyDetection

Anomaly detection (also outlier detection) is the identification of items, events or observations which do not conform to an expected pattern or other items in a dataset. Typically the anomalous items will translate to some kind of problem such as bank fraud, a structural defect, medical problems or errors in a text. Anomalies are also referred to as outliers, novelties, noise, deviations and exceptions
In particular, in the context of abuse and network intrusion detection, the interesting objects are often not rare objects, but unexpected bursts in activity. This pattern does not adhere to the common statistical definition of an outlier as a rare object, and many outlier detection methods (in particular unsupervised methods) will fail on such data, unless it has been aggregated appropriately. Instead, a cluster analysis algorithm may be able to detect the micro clusters formed by these patterns.

Anomalies might be induced in the data for a variety of reasons, such as malicious activity, e.g., credit card fraud, cyber-intrusion, terrorist activity or breakdown of a system, but all of the reasons have a common characteristic that they are interesting to the analyst. The “interestingness” or real life relevance of anomalies is a key feature of anomaly detection

# Type of Anomaly 

An important aspect of an anomaly detection technique is the nature of the desired anomaly. 

Point Anomalies. If an individual data instance can be considered as anomalous with respect to the rest of data, then the instance is termed as a point anomaly. As a real life example, consider credit card fraud detection. 

Contextual Anomalies. If a data instance is anomalous in a speciﬁc context (but not otherwise)

Behavioral attributes. The behavioral attributes deﬁne the non-contextual characteristics of an instance. For example, in a spatial data set describing the average rainfall of the entire world, the amount of rainfall at any location is a behavioral attribute

# Supervised Anomaly Detection Popular techniques
Supervised anomaly detection techniques require a data set that has been labeled as "normal" and "abnormal" and involves training a classifier (the key difference to many other statistical classification problems is the inherent unbalanced nature of outlier detection).

Density-based techniques (k-nearest neighbor, local outlier factor, and many more variations of this concept).
Subspace- and correlation-based outlier detection for high-dimensional data.
One-class support vector machines.
Replicator neural networks.
Bayesian Networks.
Hidden Markov models (HMMs).
Cluster analysis-based outlier detection.
Deviations from association rules and frequent itemsets.
Fuzzy logic-based outlier detection.
Ensemble techniques, using feature bagging,score normalization and different sources of diversity.

# Unsupervised Anomaly Detection Techniques
Unsupervised anomaly detection techniques detect anomalies in an unlabeled test data set under the assumption that the majority of the instances in the data set are normal by looking for instances that seem to fit least to the remainder of the data set. 


Clustering Techniques 
Unsupervised Neural Network 
Self-organizing map (SOM)
K-Means
Fuzzy C-Means (FCM)
Unsupervised Niche Clustering (UNC) 
Expectation-Maximization Meta Algorithm (EM) 
One -Class Support Vector Machine (OCSVM) 
