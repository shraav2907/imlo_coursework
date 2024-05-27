# imlo_coursework
This project aims to build and train a convolutional neural network (CNN) named FlowerNet for classifying flower images from the Flower102 dataset. The network is trained using PyTorch and evaluated on various metrics such as accuracy, precision, and recall.

Installation
Ensure you have installed the following:
- Python 3.6
- PyTorch
- torchvision
- scikit-learn
- Google colab for training on GPU

Dataset
The Flowers102 datset is downloaded automatically by this: 'torchvision.datasets.Flowers102' class

Testing
The 'test_model' method at the end ofthe code can be run in order to test the model on the test set.

Result
The model was trained for 200 epochs on a T4 GPU in Google Colab.
