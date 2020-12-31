---
title: "On transfer learning for chatter detection in turning using wavelet packet transform and ensemble empirical mode decomposition"
collection: publications
permalink: /publications/On_Transfer_learning
date: 2019-12-30
venue: 'CIRP Journal of Manufacturing Science and Technology'
paperurl: 'https://doi.org/10.1016/j.cirpj.2019.11.003'
---

The increasing availability of sensor data at machine tools makes automatic chatter detection algorithmsa trending topic in metal cutting. Two prominent and advanced methods for feature extraction via signaldecomposition are wavelet packet transform (WPT) and ensemble empirical mode decomposition(EEMD). We apply these two methods to time series acquired from an acceleration sensor at the toolholder of a lathe. Different turning experiments with varying dynamic behavior of the machine toolstructure were performed. We compare the performance of these two methods with support vectormachine (SVM), logistic regression, random forest classification and gradient boosting combined withrecursive feature elimination (RFE). We also show that the common WPT-based approach of choosingwavelet packets with the highest energy ratios as representative features for chatter does not alwaysresult in packets that enclose the chatter frequency, thus reducing the classification accuracy. Further, wetest the transfer learning capability of each of these methods by training the classifier on one of thecutting configurations and then testing it on the other cases. It is found that when training and testing ondata from the same cutting configuration both methods yield high accuracies reaching in one of the casesas high as 94%and 95%, respectively, for WPT and EEMD. However, our experimental results show thatEEMD can outperform WPT in transfer learning applications with accuracy of up to 95%.

[Learn more](https://doi.org/10.1016/j.cirpj.2019.11.003)