# Neural-Network-Type-Classification-TMNIST
 This code loads the MNIST dataset, prepares the data for a CNN model, creates and trains a CNN model, and stores the training history for further analysis. This code serves as a basic framework for building a CNN model for image classification.
Here is a step-by-step breakdown
1.	Imported necessary libraries including numpy, pandas, sklearn, tensorflow, and keras.
2.	Loaded the MNIST dataset using pandas and extracted the image data and labels.
3.	Split the data into a training set and a testing set using the train_test_split function from sklearn.
4.	Created a CNN model for image classification using the Keras API of TensorFlow, with several layers including Conv2D, MaxPooling2D, and Dense layers.
5.	Compiled the CNN model using the Adam optimizer and SparseCategoricalCrossentropy loss function.
6.	Visualized the model architecture using the plot_model function from Keras.
7.	Reshaped the input data to the required format for the CNN model.
8.	Trained the CNN model using the fit method with training and validation data.
9.	Stored the training history in the history variable for further analysis.




