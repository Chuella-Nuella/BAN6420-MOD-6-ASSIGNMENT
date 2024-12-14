README for the Application

Fashion MNIST Classification Using a CNN
This application classifies images from the Fashion MNIST dataset using a Convolutional Neural Network (CNN) implemented in TensorFlow/Keras.
Dataset Description
The Fashion MNIST dataset consists of grayscale images (28x28 pixels) in 10 classes:
1. T-shirt/top
2. Trouser
3. Pullover
4. Dress
5. Coat
6. Sandal
7. Shirt
8. Sneaker
9. Bag
10. Ankle boot
Each image is labeled with an integer from 0 to 9, corresponding to the above categories.
Application Features
1. Data Preprocessing: The images are normalized and reshaped for input to the CNN.
2. CNN Architecture: A six-layer CNN with convolutional, pooling, dropout, and dense layers is implemented for classification.
3. Training and Evaluation: The model is trained on 80% of the training data, validated on 20%, and tested on the test set.
4. Visualization:
Graphs for training/validation accuracy and loss.
Predicted labels displayed alongside images for manual verification.
Requirements
Python 3.8+
TensorFlow/Keras
NumPy
Matplotlib
How to Run
1. Clone the repository or download the ZIP file containing the code.
2.  Install required libraries using:  pip install tensorflow numpy matplotlib
3. Run the Code: Execute the script:
python fashion_mnist_cnn.py
4. View Outputs: The script will print the test accuracy.
Predictions for five test images will be displayed with their true and predicted labels.
Training/validation graphs will be shown for performance evaluation.

Output
1. Test Accuracy: Displays the accuracy of the model on unseen test data.
2. Prediction Visualization: Example output:
Predicted: Sneaker, True: Sneaker
Predicted: Coat, True: Coat
3. Performance Graphs: Training and validation accuracy/loss curves over epochs.





# BAN6420-MOD-6-ASSIGNMENT
Fashion MNIST Classification
