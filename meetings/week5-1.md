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
* Why not convert Y to RGB? - Motivate choice for YUV mapping algebraically
* Talk about different models and the relationship between structure of the neetwork and quantity of data in the CNN
* Run the different models with different training datasets
* Explore the depth and how small the smaller layer gets, show the difference between amount of data vs global details
* Generalizing effect of smaller kernel in middle convolutions?

* Algebraically justify the choice of mapping RGB to YUV, "why not just convert Y to RGB through the network?"
* Analyze different network models, select maybe three that vary based on how deep they are, the deeper the closer the kernel approaches the smallest convolution
* Run tests on these different models with different datasets and different parameters and collect the output data to demonstrate on the dissertation
