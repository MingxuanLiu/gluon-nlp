GluonNLP: NLP made easy
=======================

Get Started: A Quick Example
----------------------------

Here is a quick example that downloads and creates a word embedding model and then
computes the cosine similarity between two words.

(You can click the play button below to run this example.)

.. container:: demo
   :name: frontpage-demo

   `Word Embedding <https://repl.it/@szha/gluon-nlp>`_


.. include:: model_zoo.rst

And more in :doc:`tutorials <examples/index>`.


Installation
------------

GluonNLP relies on the recent version of MXNet. The easiest way to install MXNet
is through `pip <https://pip.pypa.io/en/stable/installing/>`_. The following
command installs the latest version of MXNet.

.. code-block:: console

   pip install --upgrade mxnet>=1.3.0

.. note::

   There are other pre-build MXNet packages that enable GPU supports and
   accelerate CPU performance, please refer to `this tutorial
   <http://gluon-crash-course.mxnet.io/mxnet_packages.html>`_ for details. Some
   training scripts are recommended to run on GPUs, if you don't have a GPU
   machine at hands, you may consider `running on AWS
   <http://gluon-crash-course.mxnet.io/use_aws.html>`_.


After installing MXNet, you can install the GluonNLP toolkit by

.. code-block:: console

   pip install gluonnlp


About GluonNLP
--------------

.. hint::

   You can find our the doc for our master development branch `here <http://gluon-nlp.mxnet.io/master/index.html>`_.

GluonNLP provides implementations of the state-of-the-art (SOTA) deep learning
models in NLP, and build blocks for text data pipelines and models.
It is designed for engineers, researchers, and students to fast prototype
research ideas and products based on these models. This toolkit offers four main features:

1. Training scripts to reproduce SOTA results reported in research papers.
2. Pre-trained models for common NLP tasks.
3. Carefully designed APIs that greatly reduce the implementation complexity.
4. Tutorials to help get started on new NLP tasks.
5. Community support.

This toolkit assumes that users have basic knowledge about deep learning and
NLP. Otherwise, please refer to an introduction course such as
`Deep Learning---The Straight Dope <http://gluon.mxnet.io/>`_ or
`Stanford CS224n <http://web.stanford.edu/class/cs224n/>`_.


.. toctree::
   :hidden:
   :maxdepth: 2

   model_zoo/index
   examples/index
   api/index
   community/index
