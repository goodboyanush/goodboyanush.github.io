# DARVIZ - A Visual IDE for Deep Learning

## Why DARVIZ?

Deep learning is one of the most exciting and active research area in the machine learning community. Deep learning has created almost a revolution and has yielded state-of-the-art performance in various research fields, including computer vision, speech processing, and text analytics. Various libraries/frameworks have surely contributed to this growth. Some of the widely used deep learning libraries are CAFFE, Tensorflow, Theano, Keras, Torch, and MxNet.

However, the existing libraries such as Tensorflow, Theano, Torch, Caffe, Keras etc. has the following broader challenges:

1. requires an initial large learning curve
2. knowledge of deep learning fundamentals is mandatory
3. Each library has a different syntax and has minimum communication across them. 

There is a need for simple intuitive tools to cater the needs of the diverse communities and enable them to implement and prototype deep learning models in a quicker fashion. Thus, to overcome these challenges and to make deep learning further approachable and accessible to larger audience, even to non-experts, we at IBM Research, India have launched a new IDE for deep learning called DARVIZ.

## What is DARVIZ?

DARVIZ stands for Deep Abstract Representation, Visualization, and Verification. Its a visual programming IDE, where the users could design a deep learning model using an intuitive drag-and-drop framework.  It is a creative system that could automatically write the execution ready deep learning code in Tensorflow, CAFFE, and Theano using the input, without the users having to actually write a single line of code. Thus, DARVIZ helps to flatten out the learning curve, particularly, related to understanding the specific deep learning libraries. This tool helps in extreme rapid prototyping of deep learning models and implementation of state of art papers.

Further, researchers often are interested in plugging in the publicly shared implementations in their code base. However, due to availability of various libraries and programming languages the simple task of plugging-in might be challenging. For example, a public implementation of a face recognition algorithm might be available in CAFFE, while, the user might be interested in a Tensorflow implementation of the same. In DARVIZ, one can import the code written in CAFFE (prototxt files) and export it the same code in Tensorflow. This has potentials of faster code adaptation for wider audience. 

[DARVIZ Demo](https://www.youtube.com/watch?v=Kpn6YMijMrg)

## How to access?

The current version of the tool is available at: [DARVIZ](https://darviz.mybluemix.net/). It is a free to use tool, and even a registration is not required. It could be directly used by a simple Google sign in.