
# Plant Disease Classification using Convolutional Neural Networks

This project uses a Convolutional Neural Network (CNN) to classify plant diseases from images. The dataset is derived from the PlantVillage repository and consists of over 16,000 images spanning 15 different classes.

## Project Overview

The goal of this project is to build a deep learning model capable of identifying various plant diseases from images. This is achieved through data preprocessing, augmentation, and training using TensorFlow and Keras.

## Features

- **Data Augmentation**: We use the `ImageDataGenerator` class from TensorFlow to apply various augmentation techniques like rotation, zoom, and flipping to increase the robustness of the model.
- **Model Architecture**: A custom CNN architecture is employed, featuring layers such as Conv2D, MaxPooling, Dropout, and BatchNormalization for effective learning.
- **Training and Validation**: The dataset is split into training and validation sets with a 80-20 ratio, and the model's performance is evaluated based on validation accuracy and loss.

## Installation

To run this notebook, you will need the following dependencies:

```bash
pip install tensorflow matplotlib numpy
```

## Usage

1. Clone the repository:

```bash
git clone https://github.com/yourusername/plant-disease-classification.git
```

2. Navigate to the project directory and open the notebook:

```bash
jupyter notebook Plant_Disease_Classification.ipynb
```

3. Follow the steps in the notebook to train and evaluate the model.

## Results

The model achieves an accuracy of **X%** on the validation set. 

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request for any features, bug fixes, or improvements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [PlantVillage Dataset](https://plantvillage.psu.edu/)
- [TensorFlow Documentation](https://www.tensorflow.org/)
