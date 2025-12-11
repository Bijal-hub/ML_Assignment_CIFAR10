# ML_Assignment_CIFAR10

# Optimizing Convolutional Neural Networks: A Practical Comparison of Optimizers and Learning-Rate Strategies
Subtitle: A hands-on look at Adam, SGD with Momentum, and LR Scheduling through experiments

# Contents
1. Jupyter Notebook with full experimental analysis
2. Tutorial PDF
3. Requirements file
4. Open-source licence
# How to Run the Code
1. Install Python 3.9+
2. Install dependencies: pip install -r requirements.txt
Run the notebook: .ipynb
All figures used in the tutorial will be reproduced automatically.
Load the EuroSAT Dataset(Tensorflow Datasets)
import tensorflow_datasets as tfds
dataset, info = tfds.load("eurosat/rgb", with_info=True, as_supervised=True)
Licence
This project is released under the MIT License and may be reused with attribution.
