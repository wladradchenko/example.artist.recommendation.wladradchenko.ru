# Artist Recommendation Code by KNN and Item2vec 

Artist recommendation is based on the Dataset 30Music:[http://recsys.deib.polimi.it/datasets/].

Specifically, the dataset by "session", "persons", "user" and "track". Files "session" and "track" have been transferred to "id positive" and "id negative" artist recommendation and used with "persons" dataset for recommendation and with "users" dataset for additionally predictions.

Final dataset you can download by the link:[https://yadi.sk/d/TDotca6xMA6AZg]

Artist recommendation includes to baseline (KNN) model and advanced (item2vec) ones have been trained by variants hyperparameters. 

Pre-trained models you can download by the link: [https://yadi.sk/d/QtOCQ37qvxmqwA]

P.S. Steps description on the RUS.

P.S.S. Pre-trained models archive is constructed from model knn and item2vec+data+sequence number to compare recall, precision, f1 score: 

Sequence number 01 - item2vec model trained on the dataset with rating 1 to recommend and 0 to non recommend, and hyperparameters size 200, iter 5.

Sequence number 02 - item2vec model trained on the dataset with rating >1 to recommend and 0 to non recommend, and hyperparameters size 200, iter 5. 

Sequence number 03 - item2vec model trained on the dataset with rating >1 to recommend and 0 to non recommend, and hyperparameters size 300, iter 10.
