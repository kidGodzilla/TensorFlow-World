﻿
*****************************************
TensorFLow Tutorials in TensorFLow World
*****************************************
.. image:: https://travis-ci.org/astorfi/TensorFlow-World.svg?branch=master
    :target: https://travis-ci.org/astorfi/TensorFlow-World
.. image:: https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat
    :target: https://github.com/astorfi/TensorFlow-World/issues
.. image:: https://badges.frapsoft.com/os/v2/open-source.svg?v=102
    :target: https://github.com/ellerbrock/open-source-badge/
.. image:: https://coveralls.io/repos/github/astorfi/TensorFlow-World/badge.svg?branch=master
    :target: https://coveralls.io/github/astorfi/TensorFlow-World?branch=master
.. image:: https://zenodo.org/badge/86115145.svg
   :target: https://zenodo.org/badge/latestdoi/86115145

This repository is aimed to provide simple and ready-to-use tutorials for TensorFlow. The explanations are present in the wiki_ associated with this repository. Each tutorial has a ``source code`` and its ``documetation``.

.. image:: https://github.com/astorfi/TensorFlow-World/blob/master/docs/_img/mainpage/TensorFlow_World.gif

.. The links.
.. _wiki: https://github.com/astorfi/TensorFlow-World/wiki
.. _TensorFlow: https://www.tensorflow.org/install/

============
Motivation
============

There are different motivations for this reposity. Some are TensorFlow-related which is one of the bests up to the moment that
this document is being written! The question is why this reposity has been created among all other available tutorials on the web?

~~~~~~~~~~~~~~~~~~~~~
Why using TensorFlow?
~~~~~~~~~~~~~~~~~~~~~

A deep learning is of great interest these days, the crucial necessity for rapid and optimized implementation of the algorithms
and designing architectures is the software environment. TensorFlow is designed to facilitate this goal. The strong advantage of
TensorFlow is it flexibility is designing highly modular model which also can be a disadvantage too for beginers since lots of
the pieces must be considered together for creating the model. This issue been facilitated as well by developing high level APIs
such as `Keras <https://keras.io/>`_ and `Slim <https://github.com/tensorflow/models/blob/master/inception/inception/slim/README.md//>`_
which gather lots of the design puzzle pieces. The interesting point about TensorFlow is that **its trace can be found anywhere these days**.
Lots of the researchers and developers are using it and *its community is growing with the speed of light*! So the possible issues can
be overcome easily since they might be the issues of lots of other people considering the large number of people involved in TensorFlow community.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
What's the point of this repository?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Developing open source project for the sake of just developing something is not the behind reason for this effort**.
Considering the large number of tutorials that are being added to this large community, this repository has been created to break the
jump-in and jump-out process usually happens to most of the open source projects, **but why and how**?

First of all what's the point of putting effort on something that most of the people won't stop by and take a look? What's the point of creating something that does not
help anyone in the developers and researchers community? Why spending time for something that can easily be forgotten? But **how we try to do it?** Even up to this
very moment there are countless tutorials on TensorFlow whether on the model design or TensorFlow
workflow. Most of them are too complicated or suffer from a lack of documention. There are only few avalable tutorials which are concise and well-structured
and provide enough insight for their specific implemented models. The goal of this project is to help the community with structured tutorials
and simple and optimized code implementation to provide better insight about how to use TensorFlow *fast and efficient*. It is worth
noting that, **the main goal of this project is providing well-documented tutorials and less-complicated codes**!



====================
TensorFlow Tutorials
====================
The tutorials in this repository are partitioned into relevant categories.


+----+--------------------+------------------------------------------------------------------------------+----------------------------------------------+
| #  |       topic        |   Source Code                                                                |                                              |
+====+====================+==============================================================================+==============================================+
| 1  | Start-up           |  `Welcome <welcomesourcecode_>`_  / `IPython <ipythonwelcome_>`_             |  `Documentation <Documentationcnnwelcome_>`_ |
+----+--------------------+------------------------------------------------------------------------------+----------------------------------------------+
| 2  | *TensoFLow Basics* |  `Basic Math Operations <basicmathsourcecode_>`_                             |  `Documentation <Documentationbasicmath_>`_  |
+----+--------------------+------------------------------------------------------------------------------+----------------------------------------------+
| 3  | *TensoFLow Basics* | `TensorFlow Variables <variablssourcecode_>`_                                |  `Documentation <Documentationvariabls_>`_   |
+----+--------------------+------------------------------------------------------------------------------+----------------------------------------------+
| 4  | *Machine Learning* |`Linear Regression`_                                                          |  `Documentation <Documentationlr_>`_         |
+----+--------------------+------------------------------------------------------------------------------+----------------------------------------------+
| 5  | *Machine Learning* | `Logistic Regression`_                                                       |  `Documentation <LogisticRegDOC_>`_          |
+----+--------------------+------------------------------------------------------------------------------+----------------------------------------------+
| 6  | *Machine Learning* | `Linear SVM`_                                                                |                                              |
+----+--------------------+------------------------------------------------------------------------------+----------------------------------------------+
| 7  | *Machine Learning* |`MultiClass Kernel SVM`_                                                      |                                              |
+----+--------------------+------------------------------------------------------------------------------+----------------------------------------------+
| 8  | *Neural Networks*  |`Multi Layer Perceptron`_                                                     |                                              |
+----+--------------------+------------------------------------------------------------------------------+----------------------------------------------+
| 9  | *Neural Networks*  | `Convolutional Neural Networks`_                                             |       `Documentation <Documentationcnn_>`_   |
+----+--------------------+------------------------------------------------------------------------------+----------------------------------------------+
| 10 | *Neural Networks*  | `Undercomplete Autoencoder <udercompleteautoencodercode_>`_                  |                                              |
+----+--------------------+------------------------------------------------------------------------------+----------------------------------------------+

.. ~~~~~~~~~~~~
.. **Welcome**
.. ~~~~~~~~~~~~

.. The tutorial in this section is just a simple entrance to TensorFlow wolrd.

.. _welcomesourcecode: https://github.com/astorfi/TensorFlow-World/tree/master/codes/0-welcome
.. _Documentationcnnwelcome: https://github.com/astorfi/TensorFlow-World/blob/master/docs/tutorials/0-welcome/welcome.rst
.. _ipythonwelcome: https://github.com/astorfi/TensorFlow-World/blob/master/codes/0-welcome/code/ipython/0-welcome.ipynb



.. +---+---------------------------------------------+-------------------------------------------------+
.. | # |          Source Code                        |                                                 |
.. +===+=============================================+=================================================+
.. | 1 |    `Welcome <welcomesourcecode_>`_          |  `Documentation <Documentationcnnwelcome_>`_    |
.. +---+---------------------------------------------+-------------------------------------------------+

.. ~~~~~~~~~~
.. **Basics**
.. ~~~~~~~~~~
.. These tutorials are related to basics of TensorFlow.

.. _basicmathsourcecode: https://github.com/astorfi/TensorFlow-World/tree/master/codes/1-basics/basic_math_operations
.. _Documentationbasicmath: https://github.com/astorfi/TensorFlow-World/blob/master/docs/tutorials/1-basics/basic_math_operations/basic_math_operations.rst

.. _variablssourcecode: https://github.com/astorfi/TensorFlow-World/blob/master/codes/1-basics/variables/README.rst
.. _Documentationvariabls: https://github.com/astorfi/TensorFlow-World/blob/master/docs/tutorials/1-basics/variables/README.rst


.. +---+-----------------------------------------------------+-------------------------------------------------+
.. | # |          Source Code                                |                                                 |
.. +===+=====================================================+=================================================+
.. | 1 |    `Basic Math Operations <basicmathsourcecode_>`_  |  `Documentation <Documentationbasicmath_>`_     |
.. +---+-----------------------------------------------------+-------------------------------------------------+
.. | 2 |    `TensorFlow Variables <variablssourcecode_>`_    |  `Documentation <Documentationvariabls_>`_      |
.. +---+-----------------------------------------------------+-------------------------------------------------+

.. ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
.. **Machine Learning Basics**
.. ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
.. We are going to present concepts of basic machine learning models and methods and showing how to implement them in Tensorflow.

.. _Linear Regression: https://github.com/astorfi/TensorFlow-World/tree/master/codes/2-basics_in_machine_learning/linear_regression
.. _Documentationlr: https://github.com/astorfi/TensorFlow-World/blob/master/docs/tutorials/2-basics_in_machine_learning/linear_regression/README.rst

.. _Logistic Regression: https://github.com/astorfi/TensorFlow-World/tree/master/codes/2-basics_in_machine_learning/logistic_regression

.. _LogisticRegDOC: https://github.com/astorfi/TensorFlow-World/tree/master/docs/tutorials/2-basics_in_machine_learning/logistic_regression

.. _Linear SVM: https://github.com/astorfi/TensorFlow-World/tree/master/codes/2-basics_in_machine_learning/linear_svm
.. _MultiClass Kernel SVM: https://github.com/astorfi/TensorFlow-World/blob/master/codes/2-basics_in_machine_learning/multiclass_svm/README.rst


.. +---+---------------------------------------------+----------------------------------------+
.. | # |          Source Code                        |                                        |
.. +===+=============================================+========================================+
.. | 1 |    `Linear Regression`_                     |  `Documentation <Documentationlr_>`_   |
.. +---+---------------------------------------------+----------------------------------------+
.. | 2 |    `Logistic Regression`_                   |  `Documentation <LogisticRegDOC_>`_    |
.. +---+---------------------------------------------+----------------------------------------+
.. | 3 |    `Linear SVM`_                            |                                        |
.. +---+---------------------------------------------+----------------------------------------+
.. | 4 |    `MultiClass Kernel SVM`_                 |                                        |
.. +---+---------------------------------------------+----------------------------------------+

.. ~~~~~~~~~~~~~~~~~~~
.. **Neural Networks**
.. ~~~~~~~~~~~~~~~~~~~
.. The tutorials in this section are related to neural network architectures.

.. _Convolutional Neural Networks: https://github.com/astorfi/TensorFlow-World/tree/master/codes/3-neural_networks/convolutional-neural-network
.. _Documentationcnn: https://github.com/astorfi/TensorFlow-World/blob/master/docs/tutorials/3-neural_network/convolutiona_neural_network/convolutional_neural_network.rst

.. _Multi Layer Perceptron: https://github.com/astorfi/TensorFlow-World/blob/master/codes/3-neural_networks/multi-layer-perceptron/readme.rst


.. _udercompleteautoencodercode: https://github.com/astorfi/TensorFlow-World/tree/master/codes/3-neural_networks/undercomplete-autoencoder


.. +---+---------------------------------------------+----------------------------------------+
.. | # |          Source Code                        |                                        |
.. +===+=============================================+========================================+
.. | 1 |    `Multi Layer Perceptron`_                |                                        |
.. +---+---------------------------------------------+----------------------------------------+
.. | 2 |    `Convolutional Neural Networks`_         |  `Documentation <Documentationcnn_>`_  |
.. +---+---------------------------------------------+----------------------------------------+



=================================================
TensorFlow Installation and Setup the Environment
=================================================

.. _TensorFlow Installation: https://github.com/astorfi/TensorFlow-World/tree/master/docs/tutorials/installation

In order to install TensorFlow please refer to the following link:

  * `TensorFlow Installation`_


.. image:: docs/_img/mainpage/installation.gif
    :target: https://www.youtube.com/watch?v=_3JFEPk4qQY&t=2s


The virtual environment installation is recommended in order to prevent package conflict and having the capacity to customize the working environment. The TensorFlow version employed for these tutorials is `1.1`. However, the files from previous versions can be transformed to newer versions (ex: version `1.1`) using the instructions available in the following link:

  * `Transitioning to TensorFlow 1.0 <https://www.tensorflow.org/install/migration/>`_

=====================
Some Useful Tutorials
=====================

  * `TensorFlow Examples <https://github.com/aymericdamien/TensorFlow-Examples>`_ - TensorFlow tutorials and code examples for beginners
  * `Sungjoon's TensorFlow-101 <https://github.com/sjchoi86/Tensorflow-101>`_ - TensorFlow tutorials written in Python with Jupyter Notebook
  * `Terry Um’s TensorFlow Exercises <https://github.com/terryum/TensorFlow_Exercises>`_ - Re-create the codes from other TensorFlow examples
  * `Classification on time series <https://github.com/guillaume-chevalier/LSTM-Human-Activity-Recognition>`_ - Recurrent Neural Network classification in TensorFlow with LSTM on cellphone sensor data
