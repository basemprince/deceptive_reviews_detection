# deceptive_reviews_detection

Deceptive reviews, generated by bots, are an increasing threat to the reliability of product reviews in various online platforms.
To counter their spread and to distinguish deceptive reviews from genuine ones, researchers started to use machine learning algorithms. 
Even though good results have already been achieved in this domain, the research is still ongoing to improve accuracy and performance.

This project evaluated the performance of using one-class Support Vector Machine to detect deceptive reviews online. Previous efforts were made to use both genuine and deceptive reviews to train a machine learning algorithm.

The objective of this project was to prove that only using the genuine or deceptive reviews is sufficient to produce a machine learning classifier that performs better or as good as multi-class Support Vector Machines without losing accuracy in classifications.

Through training our approach on multiple data-sets we achieved an accuracy of around 62%, which is worse than the multi-class SVM (70%). The elapsed time that was needed for training and testing outperformed the multi-class SVM and was over 60% quicker.

In conclusion, the approach of a one-class SVM is not advisable in the use case of general deceptive review detection because of its insufficient performance.
On the other hand, in other domains, like in a setting in which outlier detection is needed (e.g. authentication checks),
this approach still shows potential to outperform its multi-class counter part.
