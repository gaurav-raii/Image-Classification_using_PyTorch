# Image-Classifier-using-Pytorch
* A Deep Neural network was employed using Pytorch framework to classify among 28 X 28 grayscale images of clothing accessories. 
The network employed has input layer with 784 units, 3 hidden layers with sizes 256,128,64. The output layer is a softmax layer having 10 units.
* The network was trained with a batch size of 64 images for 10 epochs on whole training set.
* The Adam's optmizer was used with a learning rate of 0.003.
### Labels
Each training and test example is assigned to one of the following labels:

| Label | Description |
| --- | --- |
| 0 | T-shirt/top |
| 1 | Trouser |
| 2 | Pullover |
| 3 | Dress |
| 4 | Coat |
| 5 | Sandal |
| 6 | Shirt |
| 7 | Sneaker |
| 8 | Bag |
| 9 | Ankle boot |
