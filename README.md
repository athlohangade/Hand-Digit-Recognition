# Hand-DIgit-Recognition-Using-CNN

## Brief
Trained a CNN model on the MNIST dataset, using tensorflow as backend and implmented a GUI for user to choose various options for predicting the result.

## Details
1. Used **Convolutional Neural Networks** to predict handwritten digits.
2. Wrote the Convolutional Neural Network in **tensorflow** (Python).
3. The code trains the CNN model and **saves** its **checkpoint** in a directory.
4. Another **image processing** code using **OpenCV** restores the saved checkpoint while making predictions (Python).
5. User can either -
  a. **Upload** an image
  b. **Capture** an image
  c. **Display** an image
  d. **Draw** an image by gesture
6. User interaction is handled using **PyGtk 3.0**.

## Usage
-   First train the model using :
    >   python3 train.py

-   Run main.py:
    >   python3 main.py
