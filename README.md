# deep-learning-general

### 1. DL-fashion-mnist:
This project implements a deep learning approach to classify images from the Fashion-MNIST dataset and compares the performance of an ANN (Artificial Neural Network) and a CNN (Convolutional Neural Network). The dataset is preprocessed by normalizing pixel values to improve training stability. The ANN uses fully connected Dense layers with Dropout, while the CNN uses convolutional and pooling layers to extract spatial features from images. Both models are trained using the Adam optimizer with sparse categorical cross-entropy loss. The observed validation accuracy reaching ~100% is due to the validation set being taken directly from the test set without a prior separate split, leading to data overlap in evaluation. This highlights the importance of proper dataset splitting for reliable performance measurement.The goal is to compare model performance and understand how architecture choice affects image classification accuracy


### 2. CNN-mnist:
a comparison of maxpooling & average pooling with and without batch normalization on mnist dataset


### 3. CNN-mnist-1:
seeing the effect of callbacks(early stopping)


### 4. ANN-numbers:
checking  a DL model for a number dataset that we make from sklearn.make_classification with and without early stopping 


### 5. CNN_numbers_best_params:
have gridsearch cv & randomizedsearch cv for finding the best params in cnn for a number dataset that we make from sklearn.make_classification 


### 6. building_the_U_Net_model_itself_in_Keras:
Implemented a U-Net architecture from scratch in TensorFlow/Keras for image segmentation using an encoder–decoder structure with skip connections, trained with binary cross-entropy loss and Adam optimizer.!!!
