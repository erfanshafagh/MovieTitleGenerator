
# Movie Title Generator

This repository contains a project for generating movie titles using a Multilayer Perceptron (MLP) neural network built with PyTorch. The project demonstrates the use of neural networks for creative text generation.

## Project Structure

- `MovieTitleGenerator.ipynb`: The Jupyter notebook containing the implementation of the MLP for generating movie names.
- `mlp_parameters.pth`: The file where the trained model parameters are saved.
- `netflix_titles.csv`: The dataset of movie titles used for training the model.

## Requirements

To run the notebook and train the model, you will need the following packages:
- `numpy`
- `torch`
- `matplotlib`
- `pandas`

You can install the required packages using the following command:
```bash
pip install numpy torch matplotlib pandas
```

## Usage

1. Clone the repository:
```bash
git clone https://github.com/erfanshafagh/MovieTitleGenerator.git
cd MovieTitleGenerator
```

2. Open the Jupyter notebook:
```bash
jupyter notebook MovieTitleGenerator.ipynb
```

3. Run the notebook cells sequentially to train the model and generate new movie Titles.

## Notebook Overview

### Data Preparation

The notebook starts with data preparation, where it processes a dataset of movie Titles and converts them into a format suitable for training the MLP.

### Model Architecture

The MLP model is defined using PyTorch. It consists of an input layer, hidden layers, and an output layer. The notebook provides a detailed explanation of the model architecture and the reasoning behind the chosen design.

### Training the Model

The model is trained on the prepared dataset. The training process involves forward and backward propagation, and the loss is minimized using an optimizer.

### Generating Movie Titles

After training, the model is used to generate new movie Titles. The notebook includes code to generate and display several movie Titles.

### Saving the Model

The final state of the trained model is saved to a file (`mlp_parameters.pth`) for future use.

## Examples

Here are a few examples of movie titles generated by the model:

- lizen.
- super love wind.
- the flymer.
- stras.
- the like a avaan.

## Contributing

If you would like to contribute to this project, please feel free to submit a pull request or open an issue.


