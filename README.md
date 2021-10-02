# CNN
### Condensed Nearest Neighbor (CNN)
Data reduction techniques aim to simplify the training data by removing noisy and redundant data, so that, machine learning algorithms can learn faster with little or no performance degradation, as if the entire training set T is used. 

CNN was the first data reduction Algorithm. This algorithm is an incremental method that starts with adding one example of each class to the subset $S$ randomly from training set $T$. Then, for each example $x$ in $T$ is classified using the examples in $S$. if the example $x$ is incorrectly classified, it will be added to $S$. This guarantees all instances in $T$ are classified correctly. Based on this criterion, noisy examples will be retained because they are commonly classified wrongly by their $k-NN$ (whrere $k=1$).

__The CIFAR-10 dataset__
The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images.
