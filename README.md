# cifar10_keras

The CIFAR-10 dataset consists of 60000 32x32 color images divided into 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images. 

The classes in the dataset are as follows:

1. airplane
2. automobile
3. bird
4. cat
5. deer
6. dog
7. frog
8. horse
9. ship
10. truck

The classes are completely mutually exclusive. There is no overlap between automobiles and trucks. "Automobile" includes sedans, SUVs, etc. "Truck" includes only large trucks. Pickup trucks are not in the dataset.

The dataset is divided into five training batches and one test batch, each with 10000 images. The test batch contains exactly 1000 randomly-selected images from each class. The training batches contain the remaining images in random order, but some training batches may contain more images from one class than another. Between them, the training batches contain exactly 5000 images from each class. 
