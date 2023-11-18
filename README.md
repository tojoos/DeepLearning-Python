# Weather Condition Recognition with Convolutional Neural Network (CNN)

## Overview

This project implements a Convolutional Neural Network (CNN) to recognize different weather conditions based on photos. The CNN is trained on a dataset containing images of various weather conditions such as cloudy, rainy, shining, and sunrise conditions.

## Dataset

The dataset consists of a collection of labeled images representing different weather conditions. Each image is labeled with the corresponding weather condition it represents. Dataset is available under url: http://www.kasprowski.pl/datasets/weather.zip

### Dataset Structure

The dataset is organized into different folders, each representing a weather condition category. For instance:
- `cloudy/`: Images depicting cloudy weather
- `rain/`: Images depicting rainy weather
- `shine/`: Images depicting shining weather
- `sunrise/`: Images depicting sunrise scenes

## CNN Model

The CNN architecture used for weather condition recognition involves several convolutional and pooling layers followed by fully connected layers.

### Model Training

The model is trained on the labeled dataset using appropriate preprocessing techniques, data augmentation (if required), and optimization algorithms.

### Evaluation

The trained model's performance is evaluated on a separate test set to measure its accuracy in recognizing different weather conditions.

## Usage

1. **Data Preparation**: Ensure the dataset is structured correctly with labeled images in respective folders.
2. **Model Training**: Run the training script to train the CNN on the dataset.
3. **Evaluation**: Evaluate the model's performance on a separate test set using the provided evaluation script.

## Dependencies

- TensorFlow
- Jupyter to run notebooks
- Data manipulation and visualization libraries (NumPy, Matplotlib, Opencv)

## License

This project is licensed under the [MIT License](LICENSE).

### Dataset location
http://www.kasprowski.pl/datasets/weather.zip