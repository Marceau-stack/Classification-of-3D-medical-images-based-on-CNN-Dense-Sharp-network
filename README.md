# Classification-of-3D-medical-images-based-on-CNN-Dense-Sharp-network

For testing, run the last block in the code named "usable(1).ipynb",and change the unout path

EE369：Classification of 3D medical images based on CNN Dense Sharp network

basic structure: Python Keras

input data: 3D image(100x100x100),the classification(0 healthy, 1 sick)

outputdata: the classification of test CT images(0 or 1)

The machine learning model is trained on the colab plantform. To run the code, you need edit the training and testing data path in the 
code(usable(1).ipynb).

The output result is the average of three weights of three models:bestweight, model2,model3

master:

usable(1).ipynb: the overall codes

bestweight.h5py: the highest accuracy weight (batch_size=256, 10 layers, learning rate 0.001, SGD)

patch-1:

model2.h5: the trained model

weight.xx.h5py: weight

patch-2:

model3.h5: the trained model

weight.30.h5py: the best weight in model3
