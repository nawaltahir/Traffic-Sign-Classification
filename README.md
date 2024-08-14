Dataset  
German Traffic Sign Recognition Dataset (GTSRB) is an image classification dataset of traffic signs. The images are classified into 43 classes. The training set contains 39209 labeled images and the test set includes 12630 images.   
CNN Model    
The architecture of our model is:    
2 Conv2D layer (filter=32, kernel_size=(5,5), activation=”relu”)  
MaxPool2D layer ( pool_size=(2,2))  
Dropout layer (rate=0.25)  
2 Conv2D layer (filter=64, kernel_size=(3,3), activation=”relu”)  
MaxPool2D layer ( pool_size=(2,2))  
Dropout layer (rate=0.25)  
Dense Fully connected layer (256 nodes, activation=”relu”)  
Dropout layer (rate=0.5)  
Dense layer (43 nodes, activation=” softmax”)
