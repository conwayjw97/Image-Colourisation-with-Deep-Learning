# Image-Colourisation-with-Deep-Learning

Undergraduate Year 4 Individual Dissertation - "Deep Learning Methods to Solve the Inverse Problem of Artificial Image Colourisation"

## Background

This project investigated the use of Deep Learning to solve the problem of image colourisation. In order to understand which Deep Learning methods were most capable of colourisation, we implemented three Deep Learning models that seemed like the best candidates. These were a: 
* Convolutional Neural Network
* Convolutional Generative Adversarial Network
* Convolutional Variational Autoencoder

We evaluated each one with the same colourisation tasks, and used the information we gathered to determine which was the most viable solution.

## Overview

This repository contains:
```
/data            (Datasets, trained models, research notebooks)
/dissertation    (Final LaTeX report from April 2020)
/meetings        (Meeting minutes with my supervisors)
/presentation    (Project presentation slides and video)
/src             (Main code notebooks)
/status_report   (Progress report from December 2019)
/summer          (Progress report from Summer 2019)
```

## Usage

To test or use any of these models yourself, navigate to the */src* folder and follow the instructions in manual.md.

## Learn More 
To learn more about the project in detail, watch the presentation video */presentation/Presentation.mp4*. Or for a more detailed written analysis, read the final report */dissertation/report.pdf*.

## Colourisation Results

The following are colour predictions from each model for unseen images.

![Cifar-10](https://github.com/conwayjw97/Image-Colourisation-with-Deep-Learning/blob/master/dissertation/images/Cifar10Eval.png)

![Faces](https://github.com/conwayjw97/Image-Colourisation-with-Deep-Learning/blob/master/dissertation/images/FaceEval.png)

![ImageNette](https://github.com/conwayjw97/Image-Colourisation-with-Deep-Learning/blob/master/dissertation/images/ImagenetteEval.png)
