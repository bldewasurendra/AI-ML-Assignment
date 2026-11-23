# AI and Machine Learning Coursework

Coursework experiments for AI and Machine Learning using PyTorch – CIFAR-10 and FER2013 experiments.

## Repository Contents

### Exercise 01 - MLP
- **Task**: Classification on the CIFAR-10 dataset using a Multi-Layer Perceptron (MLP).
- **Notebook**: `Exercise 01 - MLP/Exercise_01_MLP.ipynb`
  - Dataset download and inspection
  - Data preprocessing and train/validation/test split
  - MLP architecture definition (Input: 3072 -> 512 -> 256 -> 10)
  - Model training with Adam optimizer and CrossEntropyLoss
  - Loss and Accuracy evaluation & visualization
  - Classification report and confusion matrix
- **Trained Model**: `Exercise 01 - MLP/models/mlp_cifar10.pth`

### Exercise 02 - CNN
- **Task**: Classification on the CIFAR-10 dataset using a Convolutional Neural Network (CNN).
- **Notebook**: `Exercise 02 - CNN/Exercise_02_CNN.ipynb`
  - Load CIFAR-10 dataset with PyTorch transforms
  - Dataset split into training, validation, and testing sets
  - CNN architecture: 2 Convolutional blocks (Conv2d, ReLU, MaxPool2d) followed by Fully Connected layers
  - Training loop with Adam optimizer and CrossEntropyLoss
  - Training vs. Validation Accuracy and Loss visualization
  - Model evaluation on test data, classification report, and confusion matrix
- **Trained Model**: `Exercise 02 - CNN/models/cnn_cifar10.pth`

### Exercise 03 - Regularisation
- **Task**: Regularisation techniques on CIFAR-10 classification using Convolutional Neural Networks (CNN).
- **Notebook**: `Exercise 03 - Regularisation/Exercise_03_Regularisation.ipynb`
  - Implementation of Dropout CNN (Dropout layers in convolutional and fully connected layers)
  - Data Augmentation techniques (RandomHorizontalFlip, RandomCrop, RandomRotation, ColorJitter)
  - Training and validation evaluation for both regularised models
  - Comparison and analysis of Baseline CNN vs. Dropout CNN vs. Data Augmentation CNN
