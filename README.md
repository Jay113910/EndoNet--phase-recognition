# EndoNet (phase recognition)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1VEYl0OOwb2EO8BY5MexFFuBkV8of19Iu)

This is a PyTorch implementation of ['EndoNet: A Deep Architecture for Recognition Tasks on Laparoscopic Videos'(2016)](https://arxiv.org/abs/1602.03012) by Twinanda et al. on Google Colab.

## Dataset
[Cholec80](http://camma.u-strasbg.fr/datasets) 

This dataset contains:
* 80 videos of cholecystectomy surgeries captured at 25 fps
* Annotations with the phase (at 25 fps) and tool presence (at 1 fps).

## Flow Chart
The whole architecture of this project

![flow chart](https://github.com/CF-Cao/EndoNet--phase-recognition/blob/main/images/Flow-chart.png?raw=true)

## Preprocessing
There are some tasks in the preprocessing step, including:
* Extract the frames from videos and the labels from label files
* Build the training and testing dataset

## Model training
The EndoNet model is based on the AlexNet.
