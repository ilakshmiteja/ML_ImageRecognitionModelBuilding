# ML_ImageRecognitionModelBuilding
I have created own handwritten digits images and using PIL library loaded the images in jupyter notebook and did certain manipulations on them. 
Later I've converted the images to numpy arrays and created a dataframe consisting the rows as image information and added a column with the image labels.
Upon, performing further pre-processing techniques I arrived at a final DataFrame which can be used for the model building.
I then split my dataframe in train and test to 70:30 and applied Support Vector Classifier, which is a boundary-based algorithm, to predict the label of the test input.
The model can be further improved using hyper-parameter tuning which will be done in upcoming phases.
