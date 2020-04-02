## Data

#### models/

Contains the layer architectures (.json), weights (.h5), and loss histories (.csv) of the trained models that were used for the evaluations shown on the report. 

Please read manual.md within the src/ folder to learn how to load these models into the notebooks yourself.

#### datasets/

Contains the ShapeSet, Face images, and Imagenette datasets used to evaluate our models. Cifar-10 is not included here, as it is downloaded inside the notebooks through the use of dedicated Tensorflow function calls.

All third-party datasets were used in this project with respect for their corresponding licences: 

* Cifar-10 is an MIT licenced dataset: https://github.com/wichtounet/cifar-10

* Face images was reused from the MIT licenced project: https://github.com/2014mchidamb/DeepColorization

* Imagenette is an Apache 2.0 licenced dataset: https://github.com/fastai/imagenette
