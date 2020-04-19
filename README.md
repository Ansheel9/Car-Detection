# Car Detection :car: 

---

Convolutional Neural Networks

Deeplearning.AI | Coursera

---

## Introduction

All of the code is in Tensorflow and Python 3. The model is trained for object detection using powerful YOLO model!

![](https://github.com/Ansheel9/Car-Detection/blob/master/nb_images/anchor_map.png)

---

## Getting Started

With all dependencies installed, jupyter notebook is provided in the course but if you want to run it on local machine (cuz you are curious to test it on gpu).

I recommend to install the Python bundle [Anaconda](https://www.anaconda.com/). All the assignments have been done with Python 3, so download the installation script accordingly. You can then install [Jupyter Notebook](http://jupyter.org/) from ``conda``.

The next step is to install TensorFlow. At the time of writing, the latest release is r0.9, after several upgrades during the course. You can refer to the [official documentation](https://www.tensorflow.org/install/#anaconda-installation). Here is the list of commands:

```
$ conda create -n tensorflow
$ source activate tensorflow
(tensorflow)$ conda install -c conda-forge tensorflow
(tensorflow)$ pip install --upgrade tensorflow-hub
```

To run it using gpu you need to additionally install ``cuda`` & ``cudann``.

---

## Instruction

To train the agent, start jupyter notebook, open <code> Autonomous_driving_application_Car_detection_v3a.ipynb </code> and execute! For more information, please check instructions inside the notebook.

---
