# MNIST-Digit-Classifier
Project Title: MNIST Digit Classifier

Description: Classify handwritten digits from MNIST dataset

Submitted by: Divya

Objective: Implement a basic convolutional neural network (CNN) for image classification. This project focuses on applying CNNs to a simple image classification problem.
# Dataset: MNIST 
# Observations: 
* In the CNN model's accuracy plot, the training accuracy increases with the number of epochs. With each iteration, the model's accuracy continues to improve. For the first two epochs, the accuracy increases rapidly.
* In the CNN model's loss plot, the loss decreases as the number of epochs increases, indicating that the model is learning effectively with each iteration. For the first two epochs, the loss decreases rapidly for the training set.
  # Result Explanation:
Test accuracy: 99.30%
Test loss 5.29%.
After data augmentation, batch normalization, and learning rate scheduling, the accuracy and loss of the model increase. The augmented samples (rotated, shifted, zoomed) are harder to classify confidently. So, the accuracy improves, but the loss increases because the predictions are less confident.
# Predictions:
9930  classified correctly
70  classified incorrectly
# Conclusions:
For the MNIST dataset, with 5-10 epochs, we can achieve 98-99% accuracy. To improve the accuracy, we can add data augmentation, batch normalization, and a learning rate scheduler.
