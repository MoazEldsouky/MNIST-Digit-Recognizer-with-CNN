## MNIST Digit Recognizer with CNN

![MNIST Digit Recognizer with CNN](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.researchgate.net%2Ffigure%2FSamples-from-the-MNIST-digit-recognition-data-set-Here-a-black-pixel-corresponds-to-an_fig1_200744481&psig=AOvVaw1JK2tqgsNpSn8xzytwrqv2&ust=1691036990564000&source=images&cd=vfe&opi=89978449&ved=0CBEQjRxqFwoTCKjZ6eqRvYADFQAAAAAdAAAAABAE)

## Description

This project is a digit recognizer that uses Convolutional Neural Networks (CNNs) to classify handwritten digits from the famous MNIST dataset. The MNIST dataset consists of 28x28 pixel grayscale images of handwritten digits (0 to 9) and is a common benchmark dataset for machine learning tasks.

The CNN model used in this project is trained on the MNIST dataset to achieve high accuracy in recognizing and classifying handwritten digits. The model's architecture and training process are discussed in the Jupyter Notebook or Python script provided in this repository.

## Getting Started

### Prerequisites

- Python 3.x
- Libraries: TensorFlow, Keras, NumPy, Matplotlib, pandas

### Installation

1. Clone the repository:
```
git clone https://github.com/MoazEldsouky/MNIST-Digit-Recognizer-with-CNN.git
```

2. Install the required libraries:
```
pip install tensorflow keras numpy matplotlib
```

### Usage

- Open the Jupyter Notebook or Python script provided in the repository.
- Follow the instructions to load the MNIST dataset, build the CNN model, and train the model.
- After training, the model's accuracy and performance can be evaluated.
- You can also use the trained model to make predictions on new handwritten digits.

### Example

```python
# Load the trained model
model = keras.models.load_model('mnist_cnn_model.h5')

# Make predictions on new data
predictions = model.predict(new_data)

# Display the results
print(predictions)
```

## Results

The CNN model achieves an accuracy of 98% on the test set, showcasing its effectiveness in recognizing handwritten digits from the MNIST dataset. Sample images and their corresponding predictions are visualized in the Jupyter Notebook or Python script.

## Contributing

Contributions to this project are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

## License

You are free to use, modify, and distribute the code for both personal and commercial purposes.

## Acknowledgments

- The CNN architecture used in this project is inspired by various online tutorials and research papers.
- The MNIST dataset is sourced from [Yann LeCun's website](http://yann.lecun.com/exdb/mnist/).

