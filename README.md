# Cifar-100-classification-using-CNN
This project is a simple image classification task using neural networks, particularly an Artificial Neural Network (ANN) and a Convolutional Neural Network (CNN). The task is to classify images from the CIFAR-10 dataset into one of the ten classes.

Here is a breakdown of the key components of the project:

1. **Importing Libraries:**
   - TensorFlow and other necessary libraries are imported.

2. **Loading Datasets:**
   - CIFAR-10 dataset is loaded, containing 60,000 32x32 color images in 10 different classes.

3. **Data Visualization:**
   - Some initial exploratory data analysis is performed, including displaying sample images from the dataset and plotting sample images with their corresponding labels.

4. **Data Preprocessing:**
   - The pixel values of the images are normalized to the range [0, 1].

5. **Artificial Neural Network (ANN):**
   - A simple ANN is created with three layers (input, hidden, and output).
   - The model is compiled with Stochastic Gradient Descent (SGD) optimizer and sparse categorical crossentropy loss.
   - The ANN is trained on the training data for 5 epochs.

6. **Evaluation of ANN:**
   - The performance of the ANN is evaluated on the test data, and metrics like accuracy are displayed.
   - Classification report is generated using scikit-learn.

7. **Convolutional Neural Network (CNN):**
   - A CNN is created with convolutional and pooling layers, followed by dense layers.
   - The model is compiled with Adam optimizer and sparse categorical crossentropy loss.
   - The CNN is trained on the training data for 10 epochs.

8. **Evaluation of CNN:**
   - The performance of the CNN is evaluated on the test data, and metrics like accuracy are displayed.
   - Classification report is generated using scikit-learn.

9. **Comparison:**
   - The results of both the ANN and CNN models are compared using classification reports.

Overall, this project demonstrates the implementation of both a simple ANN and a more sophisticated CNN for image classification on the CIFAR-10 dataset. The CNN is expected to perform better on image-related tasks due to its ability to capture spatial hierarchies in the data.
