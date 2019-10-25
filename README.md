The TensorFlow tutorials are written as Jupyter notebooks and run directly in Google Colab—a hosted notebook environment that requires no setup. Click the Run in Google Colab button.
TensorFlow is an end-to-end open source platform for machine learning. It has a comprehensive, flexible ecosystem of tools, libraries, and community resources that lets researchers push the state-of-the-art in ML and developers easily build and deploy ML powered applications.

TensorFlow was originally developed by researchers and engineers working on the Google Brain team within Google's Machine Intelligence Research organization for the purposes of conducting machine learning and deep neural networks research. The system is general enough to be applicable in a wide variety of other domains, as well.

TensorFlow provides stable Python and C++ APIs, as well as non-guaranteed backwards compatible API for other languages.

Keep up-to-date with release announcements and security updates by subscribing to announce@tensorflow.org. See all the mailing lists.

Install
See the TensorFlow install guide for the pip package, to enable GPU support, use a Docker container, and build from source.

To install the current release for CPU-only:

$ pip install tensorflow
Use the GPU package for CUDA-enabled GPU cards:

$ pip install tensorflow-gpu

Tensorflow Project Template
A simple and well designed structure is essential for any Deep Learning project, so after a lot of practice and contributing in tensorflow projects here's a tensorflow project template that combines simplcity, best practice for folder structure and good OOP design. The main idea is that there's much stuff you do every time you start your tensorflow project, so wrapping all this shared stuff will help you to change just the core idea every time you start a new tensorflow project.

So, here's a simple tensorflow template that help you get into your main project faster and just focus on your core (Model, Training, ...etc)

Table Of Contents
Main Components
Models
Trainer
Data Loader
Logger
Configuration

