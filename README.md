# imlo_coursework
This project aims to build and train a convolutional neural network (CNN) named FlowerNet for classifying flower images from the Flower102 dataset. The network is trained using PyTorch and evaluated on various metrics such as accuracy, precision, and recall.

Installation: 
Ensure you have installed the following:
- PyTorch
- torchvision
- scikit-learn

Dataset: 
The Flowers102 datset is downloaded automatically by this: 'torchvision.datasets.Flowers102' class

Training and Testing: 
- The 'imlo_cnn.ipynb' file contains the trained model.
- The 'imlo_cnn.py' file contains the code for training and testing the model. The 'test_model' method at the end of the code can be run in order to test the model on the test set.

Virtual Environment and GPU: 
The model was trained for 200 epochs on a T4 GPU in Google Colab.
