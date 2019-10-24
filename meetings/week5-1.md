## Week 5.1 - 22 Oct 2019 - Francesco Tonnolini

### Preparation
* Read chapters 10, 11, and 13 of Hands-On Machine Learning (Intro to NN, Training DNNs, CNNs)
* Investigated how the CNN functions
* Realized issues validating cifar10 dataset
* Plotted the loss for both training and testing images 
* Tried using a higher resolution dataset with images that conform to a more specific category (flowers)
* Noticed considerable validation improvement with flower dataset
* Noticed positive impact of increasing number of convolutional filters
* Investigated getting the notebook to run on local GPU
* Couldn't use Colab to train large enough datasets (tf_flowers takes max 800)
* Set up Github repository

### Minutes
* For you dissertation you should algebraically justify the choice of mapping RGB to YUV, "why not just convert Y to RGB through the network?"
* Analyze different network models, select maybe three that vary based on how deep they are, the deeper they are the closer the kernel approaches the smallest convolution, demonstrate the generalizing effect that having a kernel size close to the smallest convolution has
* Run tests on these different models with different datasets and different parameters and collect the output data to demonstrate on the dissertation
