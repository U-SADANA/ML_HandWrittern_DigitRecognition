# ML_HandWrittern_DigitRecognition

DATASET : Set of 70,000 small images of digits handwrittern labeled with digits they represent.
#### Each image has 784 (28*28) features.
#### EACH IAMGE IS 28*28 pixels and EACH FEATURE reprsents one pixel intensity from 0(white) to 255(black).

Normalise the train and test inputs by 255.
Classification Model

The Sequential model is a linear stack of layers : allows you to create models layer-by-layer for most problems.

Flatten : is used to flatten the input : Does not affect the batch size.Flattening is converting the data into a 1-dimensional array for inputting it to the next layer.
Dense layer is the regular deeply connected neural network layer.

categorical_crossentropy is defined as categorical crossentropy with integer targets with two or more label classes. 
