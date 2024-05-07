# Feature-selection-for-few-short-building-instance-Classification-using-genetic-algorithm
see readme file.

This project aims to classify urban building types, particularly mixed-usage structures(like commercial+residance), from Street-View images we created a mixed type dataset then Leveraging Genetic Algorithms and Contrastive Learning, it utilizes ResNet-50 and DINOv2 models to classify given dataset of single-type buildings . In the second file, it trains a model to extract image embeddings and calculate class-wise centroids for single-type buildings, which are then used to find the percentage composition of the mixed-type buildings. Triplet Loss is employed for training, facilitating accurate labeling of mixed-type structures.
