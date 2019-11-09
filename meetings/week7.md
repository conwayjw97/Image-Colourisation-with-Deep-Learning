## Week 7 - 7 Nov 2019 - Roderick Murray-Smith & Francesco Tonnolini

### Preparation
* Managed to get Colab to load all 50'000 sample images from cifar10 using the fit_generator method with a custom image loader function
* Attempted to get the CNN to also output its feature maps for each layer in order to better understand in detail how the model works, however haven't managed to get that working
* Worked on even shallower CNN models in order to find an optimal model for the cifar10 dataset, all models so far result in overfitting before they're able to produce sufficient outputs for the validation images, Francesco believes this is caused by an excess of parameters even for the shallow model

### Minutes
* Make a start on your report, start with the introduction and lit review
* Talk about colourization as an Inverse Problem and why you would use CNN's to solve it
* Look at how previous projects have approached the problem and what results they acheived with their methods 
* Talk about how modifying the CNN's hyperparameters, model, and dataset has an impact on the result 
* Investigate how other potential sources of side information can assist the CNN, considering the potential candidates to use in your own project
* As an example of using side information to assist a CNN, have a look at the work that Zeynep Akata from Tubingen University did on her bird image project http://proceedings.mlr.press/v48/reed16.pdf
