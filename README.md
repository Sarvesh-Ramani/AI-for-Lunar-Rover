# AI-for-Lunar-Rover

This project is aimed at developing a Machine Vision system for obstacles detection on the Lunar Surface.

About the Dataset:
This dataset contains 9766 realistic renders of lunar landscapes and their masks (segmented into three classes: sky, small rocks, bigger rocks).
->Additionally, a csv file of bounding boxes and cleaned masks of ground truths are provided.
An interesting feature of this dataset is that the images are synthetic; they were created using PlanetsideSoftware's Terragen.
Dataset: https://www.kaggle.com/datasets/romainpessia/artificial-lunar-rocky-landscape-dataset

Libraries Used:
Os:The OS module in Python provides functions forinteracting with the operating system.

OpenCV:OpenCV-Python is a library of Python bindingsdesigned to solve computer vision problems.

Keras: Keras is an open-source high-level NeuralNetwork library,whichiswrittenin Python iscapable enough to run on Theano, TensorFlow, or CNTK.

Numpy:  It is a library for the Python programming language, adding support for large, multi-dimensional arrays and matrices, along with a large collection of high-level 
mathematical functions to operate on these arrays.

Tensorflow: TensorFlow is a Python library forfast numerical computing created and released 0y Google. It is a foundation library that can be used to create Deep Learning 
models directly or by using wrapper libraries that simplify the process built on top of TensorFlow.

Matplotlib: Matplotlib is a python library used to create 2D graphs and plots by using python scripts.It has a module named pyplot which makes things easy for plotting by 
providing features to control line styles, font properties, formatting axes etc.

Segmentation_models: Python library with Neural Networks for Image Segmentation based on Keras and TensorFlow . The main features of this library are: High level API,
4 models architectures for binary and multi-class image segmentation (including legendary Unet) 25 available backbones for each architecture.

Sklearn: Scikit-learn (Sklearn) is the most useful and robust library for machinelearning in Python. It provides a selection of efficient tools for machine learning 
and statistical modeling including classification, regression, clustering and dimensionality reduction via a consistent interface in Python.

Overview:
The project gives a val_iou score of 0.24. The model is trained with the U-Net Architecture as the backbone using convolutional neural network concept. 
https://blog.paperspace.com/unet-architecture-image-segmentation/
