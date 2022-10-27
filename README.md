# PRID

This repository has been made for Zewail City Internship in Summer 2022. We were working on the Zewail City Surveillance system. We were part of the people analytics team who is responsible for person re-identification techniques. You Will find some notebooks of some trials that may help you to understand and be familiar with Torch-Reid.

## The main final work is in these files:

1) Classify_Data_Final.ipynb : This is a python script that can convert the Zewail city dataset into an appropriate form of train, test, and query folders, which can be able to register in Torch-Reid.

2) Best_Osnet.ipynb: This notebook is applying Osnet_X1_0 pre-trained model on market1501 and fine-tuned it on the Zewail City dataset.

3) intern_single_query.ipynb: This notebook works inside Torch-Reid to allow it to be able to accept a single query image and search for its best match of it in the test "gallery" dataset.
