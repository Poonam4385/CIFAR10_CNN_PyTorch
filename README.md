# CIFAR-10 Image Classification with PyTorch

A Convolutional Neural Network (CNN) built using **PyTorch** to classify images from the **CIFAR-10 dataset** into 10 categories.

## Dataset

CIFAR-10 contains **60,000 color images (32×32 pixels)** across 10 classes:

Airplane, Automobile, Bird, Cat, Deer, Dog, Frog, Horse, Ship, and Truck.

- Training images: 50,000
- Test images: 10,000

## Model

Two CNN models were developed:

- **Baseline CNN:** Conv2D → ReLU → MaxPool → Fully Connected Layers
- **Improved CNN:** Added Data Augmentation, Batch Normalization, Dropout, and an additional convolutional layer

## Results

| Model | Test Accuracy |
|---|---:|
| Baseline CNN | 69.52% |
| Improved CNN | **79.65%** |

**Improvement: +10.13 percentage points**

## Technologies

- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- Google Colab

## Key Learnings

- Building CNNs with PyTorch
- Dataset and DataLoader
- Forward propagation and backpropagation
- Cross-Entropy Loss and Adam optimizer
- Data augmentation
- Batch Normalization and Dropout
- Model evaluation
- Saving and loading PyTorch models

  ## Author

Poonam Sunil Lonkar
M.Sc. Data Science & Analytics
GitHub: Poonam4385
