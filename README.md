# Fashion-MNIST Classifier

A deep learning project that classifies 28x28 grayscale clothing images into 10 categories
(T-shirt, Trouser, Pullover, Dress, Coat, Sandal, Shirt, Sneaker, Bag, Ankle boot).

## Project Structure

```
fashion-mnist-classifier/
├── data/
│   └── fmnist_small.csv                  # 6,000 images (label + 784 pixel columns)
├── models/
│   └── fashion_model.pt                  # Trained model weights (saved by the notebook)
├── notebooks/
│   └── fashion_mnist_exploration.ipynb   # Data exploration, training, and evaluation
├── requirements.txt
└── README.md
```

## Setup

```bash
pip install -r requirements.txt
```

## Usage

Open the notebook and run the cells from top to bottom:

```bash
jupyter notebook notebooks/fashion_mnist_exploration.ipynb
```
