# ML-with-GPT
📌 Dataset loading: Uses mnist.load_data() to load the classic handwritten digit dataset (28×28 grayscale images).

📌 Preprocessing: Normalizes pixel values to [0, 1] range and converts integer labels to one-hot encoded vectors with to_categorical().

📌 Model architecture: Simple Sequential model with:

A Flatten layer to convert 28×28 images into 784-length vectors.

A hidden Dense layer with 128 neurons and ReLU activation.

An output Dense layer with 10 neurons (for 10 digit classes) and softmax activation.

📌 Compilation: Uses Adam optimizer, categorical crossentropy loss (for multi-class classification), and tracks accuracy.

📌 Training: Fits the model for 5 epochs, with validation on test data to monitor generalization.

📌 Evaluation: Finally evaluates on test data and prints the test accuracy.

✅ Purpose: Demonstrates a simple neural network for digit classification using Keras with minimal code.
