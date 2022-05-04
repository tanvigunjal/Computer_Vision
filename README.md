# Computer_Vision

# Dataset 

We consider an image classification task using the widely used CIFAR-10 dataset. This dataset consists of 50,000 training images of 32x32 resolution with 10 object classes, namely airplanes, cars, birds, cats, deer, dogs, frogs, horses, ships, and trucks. Each class has 6000 images per class. the test set contains 10,000 image.

![Screenshot (107)](https://user-images.githubusercontent.com/80224279/166724323-c023a961-bde7-4a06-a098-3b168df4421e.png)

In Deep Learning using basic operations.ipynb we implimented a simple two-layer neural network and its training algorithm based on back-propagation using only basic matrix operations. 

And then implimeted the same architechure using PyTorch library. 
nput_size = 32 * 32 * 3
hidden_size = [50]

num_classes = 10

num_epochs = 10

batch_size = 200

learning_rate = 1e-3

learning_rate_decay = 0.95

reg=0.001

num_training= 49000

num_validation =1000
