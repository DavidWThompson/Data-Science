The cifar-10 dataset is a commonly used 'toy' dataset which is a labelled subset of the 80 million tiny images dataset. It contains 60,000 32x32 pixel images from 10 classes (6,000 images per class)

The aim of this code, written in Python, found in this folder is to assign each image within the set test to it's correct class. 

Assignments made purely at random will achieve an accuracy of 10%, with humans being capable of around an accuracy of around 94%.

This is a commonly studied dataset, with the state of the art accuracy improving from 79% in 2010 to the current record of 99.5% set in 2021.

This code was written over the course of 2-3 days (including the time taken to train each model). The first model had an accuracy of 55%.

Through the tuning of various hyper-parameters this was increased to 78%.

While this accuracy is closer to the state of the art for 2010 than it is for today, it is this author's humble opinion, a reasonable effort given extremely tight restraints on both time and computation power.

In this folder you will find a Jupiter Notebook of the full source. If you wish to run this code yourself, a word of warning:

When run on this author's home PC (11th Gen Intel i5-11400F @ 2.60GHz and GeForce RTX 3060) the training of all 6 models did take hours rather than minutes.
