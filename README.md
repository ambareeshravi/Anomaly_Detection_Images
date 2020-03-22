# Anomaly_Detection_Images
Anomaly detection in Images - HAM10000 dataset

Anomaly detection has multiple definitions depending on the problem statement under which it is applied. But in this case, I'm resoring to the following defenition:
Any data that comes out of the distribution of the desired operating data.

Since there is no 'truly generic' way identify anomaly (at least not yet), we consider anything that comes out of the distribution of training examples as anomaly (both unseen data and outliers).

For this project, I'm going to experiment different methods to detect anomalous images:

1. AutoEncoders
2. PCA / LLE + Clustering
3. Histogram / Spectogram analysis