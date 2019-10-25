## Week 5.2 - 25 Oct 2019 - Roderick Murray-Smith & Francesco Tonnolini

### Preparation
* Tried using a higher resolution dataset with images that conform to a more specific category (flowers)
* Noticed considerable validation improvement with flower dataset
* Noticed positive impact of increasing number of convolutional filters
* Tried a dataset with images with similar charactersitics (human faces)
* Noticed how this was less susceptible to overfitting and resulted in better testing validation
* Began collecting outputs for different CNN models to notice the effect that kernel size and number of layers has on output
* Couldn't use Colab to train large enough datasets (tf_flowers takes max 800)
* Investigated getting the notebook to run on unvirsity GPU cluster

### Minutes
* 400x400 sized images are probably bigger than necessary
* Investigate the fit_generator function and loading images by batches in order to use less Colab RAM
* Spend some time analyzing what you've learned so far and understanding what you've seen so far from the CNN outputs (why is it outputting colour in particular places, how is it training itself, how the way it's working in detail affects the output, etc.)
