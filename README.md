# Rock vs Mine Prediction

This project aims to classify objects as either "Rock" or "Mine" using sonar data. The dataset consists of 60 features representing the intensity of sonar returns at different angles, and the label indicates whether the object is a rock or a mine.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Model](#model)
- [Results](#results)
- [Contributing](#contributing)


## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/Rock_vs_Mine_Prediction.git

## Usage

To use the model, you can either run the Jupyter notebook provided or use the Python script to make predictions. Here's an example of how to use the predictive system:

1. Open the Jupyter notebook `Rock_vs_Mine_Prediction.ipynb`.
2. Run all the cells sequentially.
3. You can modify the `input_data` variable in the "Making a Predictive System" section to test different data points.

## Project Structure
Rock_vs_Mine_Prediction/              
├── Rock_vs_Mine_Prediction.ipynb  # Jupyter notebook for the project  
├── requirements.txt # List of dependencies  
└── README.md # Project description
## Model

The model used in this project is a Logistic Regression classifier, implemented using the `scikit-learn` library. The dataset was split into training and testing sets, with the model trained on the training set and evaluated on the test set.

## Results

- **Training Accuracy:** *83%*
- **Test Accuracy:** *76%*

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.
