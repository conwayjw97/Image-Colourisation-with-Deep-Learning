
## *Generative Models and Inverse Problems for Image Colourisation and Restoration*
#### *James Conway*
#### *2247492*

## Proposal
### Motivation
The colourisation of black and white images is currently carried out in a time consuming
manual process mainly using photo-shop software which can take up to several months in some
cases and requires particular artistic skills. Up till now, no fully automated colourisation tools have been developed. The availability of an automated colourisation system would mean that more people will be able to use colourisation technology, and that projects involving the colourisation of numerous images, such as in the case of video colourisation, can be carried out much more efficiently. Automatic colourisation also has other technical uses, for example in assisting grey-scale image recognition, as the images can be coloured, and then the colours of the image can also be evaluated in order to classify its contents. This could be particularly useful for some technologies such as night vision and ultrasound imaging.

### Aims
The aim of this project is to investigate how effectively Deep Learning models can
be used to solve the problem of image colourisation. In order to achieve this we will:
- Explore YUV and LAB colour encodings and which encoding works best when used with the generative model.
- Examine the most effective model of CNN capable of performing the task.
- Find the optimal hyper-parameters for the network to most effectively train on the
widest variation of image data.
- Create a dataset of training images which can train the CNN to generalize as effectively as possible.
- Examine the best forms of data augmentation to apply to a model's provided dataset.
- Investigate the best forms of additional information the network can be provided with to
best help it colourise.
- Explore the application of Convolutional Generative Adversarial Networks and Variational Autoencoders to solving the problem.

## Progress
- Developed a Deterministic Convolutional Neural Network for colourisation which is most capable to preventing overfitting while training on cifar10.
- Read and took notes on a multitude of academic papers which also investigate colourisation and compared their approachs to the problem.
- Investigated the cifar10, tf_flowers, CelebFaces, and ImageNet datasets to determine which is best to use for the problem.
- Begun drafting Introduction and Analysis/Requirements sections of report.
- Recorded the effect a range of different hyperparameters have on traning in order to find the optimal parameters.
- Implemented data augmentation to reduce overfitting.
- Implemented regularisation (L1 and Droput) to reduce overfitting.
- Wrote generator function in order to load images by batch during training to reduce RAM usage.
- Examined additional sources of information which can assist the CNN:
	- Low-High level semantic feature descriptors.
	- Training dataset pruning based on image classification.
	- User input image labelling.
	- User input text description.
	- User input brush colouring.
- Implemented grayscale input image classifier which can then pick training images from cifar10.
- Wrote code to save and load trained models for reuse.

## Problems and risks
### Problems
- Initial difficulty learning how CNNs worked.
- Took a long time training and retraining modified CNN models in order to find an optimal one.
- cifar10 CNN outputs still patchy.
- Low-Mid level semantic feature descriptors were particularly difficult to learn how to implement, didn't manage to.
- Had difficulty implementing a Generative Adversarial Network with Keras, still haven't managed to.

### Risks
- Chosen CNN model and parameter tuning might only be optimal for cifar10 dataset. **Mitigation**: will investigate also using ImageNet.
- Begun CNN development with YUV image encoding before investigating whether LAB would have been better. **Mitigation**: will test LAB after final model is chosen, also found a paper which tried both encodings for colourisation which I could learn from.
- Colab could prove too slow to use for very large datasets like ImageNet. **Mitigation**: now have access to the University GPU cluster which I should attempt to use at least once to see if it's a major improvement.

## Plan
# Semester 2
* **Week 1 - 3** Finish and polish GAN and VAE codebase.
	- **Deliverable**: Runnable Python files/notebooks containing the project code.
* **Week 4** Collect network evaluations to compare parameters/models/dataset for the report.
	- **Deliverable**: Metrics and outputs.
* **Week 5** Finish gathering literature to cite and discuss on report.
* **Week 6-8** Report first draft writing.
	- **Deliverable**: First draft.
* **Week 8-10** Report rewriting and polishing.
	- **Deliverable**: Final draft.
