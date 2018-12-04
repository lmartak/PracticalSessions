# Deep Learning Hands-On Exercises

The exercises in this repository are based off of the [practical sessions](https://github.com/tmlss2018/PracticalSessions) of the [Transylvanian Machine Learning Summer School](https://tmlss.ro), happening in Cluj-Napoca, Romania between 16-22 July 2018. The sessions cover topics from basic knowledge of [numpy](http://www.numpy.org/), [tensorflow](https://www.tensorflow.org/) and [sonnet](https://github.com/deepmind/sonnet) to computer vision, recurrent models, generative models and reinforcement learning.

## Usage
To access the exercises please download them and place them in your Google Drive. The simplest way to do this is to check out the git repository, then use the "Folder Upload" tool in GDrive. Use [colab](https://colab.research.google.com) to view or edit them.

### Preparing for the sessions
It is highly recommended for you to go through the [introductory](./introductory) notebooks (all the notebooks named as `Intro_*.ipynb`) to familiarize yourself with the environment that will be used.

Specifically, for the Session#1 you might want to go through introductions to [Colab](./introductory/Intro_Colab.ipynb), [NumPy](./introductory/Intro_Numpy.ipynb), [Plotting](./introductory/Intro_Plotting.ipynb) and [Tensorflow and Sonnet](./introductory/Intro_Tensorflow_and_Sonnet.ipynb). The introduction to [Learning a Distribution](./introductory/Intro_Learning_a_Distribution.ipynb) with TensorFlow will come of use specifically in Session #4.

Don’t forget to bring your laptop for the hands-on sessions. There are no special hardware or software requirements. All you need is a browser.

All the code for the practical sessions will run in [ColabX, google’s public framework for machine learning experiments](https://colab.research.google.com/notebooks/welcome.ipynb). To use ColabX, you must have a gmail account, and allow ColabX to access your gdrive. If you have privacy concerns, it is recommended for you to create a new gmail account dedicated for this purpose. If you don’t have a gmail account, please create one to be able to run the materials.

### Tips

#### Using Sonnet
Sonnet does not possess an exhaustive documentation such as TensorFlow, but you can find some usage examples [here](https://deepmind.github.io/sonnet/), browse Sonnet modules [here](https://deepmind.github.io/sonnet/py-modindex.html) and finally for the implementation / API details, the most competent reference is the [source code](https://github.com/deepmind/sonnet).

#### Using Colab
It is useful to set yourself a shortcut for **Cycle form view** in **Tools** -> **Keyboard preferences** to something convenient to be able to quickly show/hide Code and Form parts of the Colab-specific hybrid cells.


## Schedule

The hands-on tutorials will be scheduled into multiple separate sessions according to the interest of the audience after the Session #1.

### Session #1: Introductory session
#### Part 1

**Date**: 24.10.2018

**Time**: 16:00

**Location**: Room 4.08 (4th floor), [FIIT STU in Bratislava](https://goo.gl/maps/w3RRaUHWkX12)

**Expected duration**: ~ 1 hour (++)

##### Planned content:
* I will give a short talk to briefly introduce the basic concepts related to supervised learning with neural networks.
* You will train a simple neural network model to classify [MNIST](http://yann.lecun.com/exdb/mnist/) digits while exercising usage of `TensorFlow` and `Sonnet` to define and train the model, `numpy` and `tf.data` API to manipulate the dataset and `matplotlib` to visualize the training progress.
* Session will be open-ended to provide space for discussions.

#### Part 2

**Date**: 04.12.2018

**Time**: 13:00 - 15:00

**Location**: Room 4.08 (4th floor), [FIIT STU in Bratislava](https://goo.gl/maps/w3RRaUHWkX12)

**Expected duration**: ~ 1-2 hours

##### Planned content:
* Common review of `Intro_Tensorflow_and_Sonnet.ipynb` Colab notebook.
* Common implementation of `Comprehensive_Exercise.ipynb` using TensorFlow and Sonnet.
* Bonus: implementation of `Comprehensive_Exercise.ipynb` using `tf.keras` API.

### Session #2: Convolutional Neural Networks and Computer Vision

...

### Session #3: Recurrent Neural Networks and Natural Language Processing

...

### Session #4: Generative Modelling with VAEs and GANs

...

### Session #5: Reinforcement Learning

...

## Acknowledgments
The materials in this repository come from [TMLSS2018](https://tmlss.ro) lab instructors:

* David Szepesvari - [introductory](./introductory)
* Viorica Patraucean - [vision](./vision)
* Wojtek Czarnecki - [rnn](./rnn)
* Mihaela Rosca - [generative](./generative)
* Diana Borsa - [rl](./rl)

_Note: you can find solutions to these exercises as well as possible future updates in the [original repository](https://github.com/tmlss2018/PracticalSessions) of TMLSS Practical Sessions._