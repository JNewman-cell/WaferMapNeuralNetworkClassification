# WaferMapNeuralNetworkClassification

In this code I used machine learning to create a model that classified real wafer map data with >90% accuracy using the WM-811K Wafer Map Dataset. I made a 14 layer neural network that was able to classify different types of wafer maps. My model included augmentations to the original data to aid learning, a feature layer which used convolution and pooling to extract features from the maps, and a classifier which took in all the parameters of my feature layer and outputted each map into one of the five classes. I used a sample of 1800 wafer maps and split them into a 70% train and 30% test split to enable a greater accuracy of the model. Using 10 epochs, my model achieved a loss of 0.3 and a validation accuracy of 93%. 

## Final Results
I created an overall accuracy and per class accuracy functions to identify which classes were incorrectly classified. Using these functions and confusion matrices, I further tweaked my model so that the accuracy improved. Testing it on more of the dataset, it scored a >90% prediction rate.
