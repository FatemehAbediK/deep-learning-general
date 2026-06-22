# deep-learning-general

### 1. DL-fashion-mnist:
This project implements a deep learning approach to classify images from the Fashion-MNIST dataset and compares the performance of an ANN (Artificial Neural Network) and a CNN (Convolutional Neural Network). The dataset is preprocessed by normalizing pixel values to improve training stability. The ANN uses fully connected Dense layers with Dropout, while the CNN uses convolutional and pooling layers to extract spatial features from images. Both models are trained using the Adam optimizer with sparse categorical cross-entropy loss. The observed validation accuracy reaching ~100% is due to the validation set being taken directly from the test set without a prior separate split, leading to data overlap in evaluation. This highlights the importance of proper dataset splitting for reliable performance measurement.The goal is to compare model performance and understand how architecture choice affects image classification accuracy


### 2. CNN-mnist:
To compare of maxpooling & average pooling with and without batch normalization on mnist dataset,This project applies different Convolutional Neural Network (CNN) architectures to the MNIST handwritten digit dataset using TensorFlow/Keras. It includes a simple CNN model, a deeper CNN with MaxPooling and AveragePooling layers, and an improved version using Batch Normalization to enhance training stability and performance. Across experiments, CNNs consistently achieve high accuracy (around 98–99%), showing strong capability in extracting spatial features from images. Deeper models and normalization layers help improve convergence and generalization compared to simpler architectures.


### 3. CNN-mnist-1:
This project uses a simple Artificial Neural Network (ANN) built with TensorFlow/Keras to classify handwritten digits from the MNIST dataset. The model consists of a Flatten layer followed by two fully connected Dense layers with ReLU activation and a Softmax output layer. The data is normalized before training, and early stopping is used to prevent unnecessary training once performance stabilizes. The model achieves strong accuracy on both training and test sets, showing the effect of callbacks(early stopping).


### 4. ANN-numbers:
In this study, I built and trained a deep learning model on a synthetic dataset generated using sklearn.make_classification to evaluate its performance on a structured classification problem for tabular data. The main objective was to compare model behavior with and without early stopping. Early stopping was used as a regularization technique to monitor validation loss during training and automatically halt the process when performance stopped improving. This helped prevent overfitting and reduced unnecessary training epochs. By comparing both approaches, I observed how early stopping improves generalization and stabilizes validation performance, while also making training more efficient.

### 5. CNN_numbers_best_params:
have gridsearch cv & randomizedsearch cv for finding the best params in cnn for a number dataset that we make from sklearn.make_classification 


### 6. building_the_U_Net_model_itself_in_Keras:
Implemented a U-Net architecture from scratch in TensorFlow/Keras for image segmentation using an encoder–decoder structure with skip connections, trained with binary cross-entropy loss and Adam optimizer.!!!
