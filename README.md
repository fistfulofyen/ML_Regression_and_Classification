# Application of Mechine Learning Projects

This repository contains machine learning projects that focus on regression and classification tasks using the NumPy, scikit-learn and Tensorflow libraries. Various datasets are used for these projects. Datasets used are mentioned in the project description.

## Projects Included

- **Wine quality classification and regression**
  - Datasets: [Red Wine Quality](https://archive.ics.uci.edu/ml/datasets/wine+quality), [White Wine Quality](https://archive.ics.uci.edu/ml/datasets/wine+quality)
  - Description: In this project, the goal is to classify wine quality as 'bad' or 'good' using classification model. It demonstrates classification algorithms with scikit-learn. a regression model is also used to determine sample quility.

- **Magic gamma telescope**
  - high energy gamma particles in a ground-based atmospheric Cherenkov gamma telescope
  - Datasets: [MAGIC Gamma Telescope](https://archive.ics.uci.edu/dataset/159/magic+gamma+telescope)

- **Multi task model with keras**
  - This Jupyter Notebook demonstrates a multi-task learning setup using TensorFlow and Keras. Multi-task learning involves training a model to perform multiple related tasks simultaneously. In this example, the model is trained to predict both the digit label and the color of a handwritten digit image.
  - The MNIST dataset is used in this example. The dataset consists of grayscale images of handwritten digits (0 to 9). Each digit is associated with a label indicating the digit itself, and in this case, a color label (0 for red, 1 for green) is also introduced.
  - The model architecture involves shared convolutional layers followed by separate branches for digit and color predictions. The shared layers capture general features from the input image, and the separate branches learn task-specific predictions.

![Blurly Image](https://i.stack.imgur.com/PHDCw.png)

- **Least square regression**
  - Lab1 
  - Trade-off between Overfitting and Underfitting is investigated
  - $$\ t = \sin(4\pi x + \frac{\pi}{2}) + \epsilon \$$

- **binary classification logistic regression**
  - Lab 2
  - breast cancer wisconsin dataset (classification)
  - ROC and PR curve are graphed

- **K Nearest Neighbor**
  - Lab 3
  - K Nearest Neighbor is used on boston housing dataset
  - Best K value is determined

- **Neural Network Classifier with Two Hidden Layers**
  - Lab 4
  - Early stop, SGD
  - Number of hidden layer units is changed and compared to find the optimal n1, n2.

- **k means clustering**
  - Lab 5
  - Image processing and compression
  - Effect of random initialization is observed

## Requirements

- Python 3.x
- NumPy (install using `pip install numpy`)
- Pandas (install using `pip install pandas`)
- scikit-learn (install using `pip install scikit-learn`)
- TensorFlow (install using `pip install tensorflow`) - mine is version 2.12.0
- Other libraries when necessary, see project import.


## License

This project is licensed under the MIT License