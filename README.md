# DL-Build-and-Train-a-CNN-for-MNIST-Handwritten-Digit-Recognition

The goal of this project is to build a Convolutional Neural Network (CNN) to recognize handwritten digits from the MNIST dataset. The MNIST dataset contains 70,000 grayscale images of digits (0-9), each 28x28 pixels in size. Using TensorFlow and Keras, we will create and train a deep learning model to classify these digits accurately.


1. Libraries: TensorFlow and Keras for building the CNN; Matplotlib for visualization.
2. Data Loading and Preprocessing: Normalize pixel values and reshape data to fit the CNN input format.
3. Model Building: Three Conv2D layers with ReLU activation and max pooling, followed by Dense layers.
4. Model Compilation: Using Adam optimizer and categorical cross-entropy loss.
5. Model Training: Training the model for 5 epochs with validation data.
6. Model Evaluation: Test accuracy is printed to see how well the model performs.
7. Visualization: Plotting the training and validation accuracy over epochs.
