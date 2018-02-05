---
layout: post
title: Tensorflow 1.5 - what you need to know
permalink: /tensorflow-1_5
published: true
images:
  - url: /assets/tensorflow/tensorflow1.5.png
---

**Introduction**

TensorFlow is a very popular open-source library that is written in Python, C++ and CUDA. It’s uses span a range of tasks. Chief amongst them, is its use in machine learning applications for building neural networks.

The TensorFlow library has seen many releases since 2015, and Google announced the latest update a couple of days back – TensorFlow 1.5. According to the team, they were monitoring “feedback about the programming style of TensorFlow, and how developers really wanted an imperative, define-by-run programming style”.



**Eager Execution for TensorFlow**

This has led to the inclusion of Eager Execution for TensorFlow. It’s available as a preview with the latest build and is available to the general public. With Eager Execution for TensorFlow enabled, users can now execute TensorFlow operations as soon as they are called from Python. Not only does this make it easier for TensorFlow newcomers, it also makes research projects more insightful and intuitive.

You can learn more about Eager Execution [here](https://github.com/tensorflow/tensorflow/tree/r1.5/tensorflow/contrib/eager).



**TensorFlow Lite**

The developer preview of TensorFlow Lite is also available as part of the latest release. TensorFlow Lite is TensorFlow’s solution for mobile and embedded devices. With it, you can take a trained TensorFlow model and convert it to a .tflite file. This can then be executed on a mobile device. Let’s say you want to build a model to classify an image. Using TensorFlow Lite, a trained model can be deployed to the mobile device and the image will be classified directly on the device.

You can read more about TensorFlow Lite [here](https://www.tensorflow.org/mobile/tflite/).



**What else is there in TensorFlow 1.5?**

Apart from that, below is a list of some of the other minor changes and additions:

CUDA 9 and cuDNN7 support
The addition of auto_correlation to tf.contrib.distributions.
Changed tf.contrib.distributions docstring examples to use tfd alias rather than ds, bs.
Fixed correctness bug in CPU and GPU implementations of Adadelta.


**So, how to install TensorFlow 1.5?**

It just takes a line of code. To install TensorFlow 1.5, use the usual pip installation (pip3 if you’ve upgraded to python3):

$  pip install --ignore-installed --upgrade tensorflow


You can access TensorFlow’s GitHub page [here](https://github.com/tensorflow/tensorflow/releases).



**Our take on this**

All the minor features and changes considered, Eager Execution for TensorFlow is one of the most anticipated additions to the library. With this enabled, the user no longer needs to execute a pre-constructed graph with Session.run(). A welcome change, indeed.