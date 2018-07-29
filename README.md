# intro-deep-learning
Deep learning is an exciting topic in artificial intelligence. It has a lot of mystique surrounding it that can make it hard to understand what it entails. The goal of this project is to aggregate the best resources and provide introductory deep learning tutorials in the form of Jupyter Notebooks. The content will be explained as simply as possible, and the intended audience is anyone who has prior programming experience and interest in machine learning. I'm a deep learning hobbyist, and I hope that by putting together through these notebooks, I can more deeply (pun intended) understand concepts along the way and help you learn as well.

## Knowledge needed to get started

For these notebooks, you'll need to be able to understand Python. If you are unfamiliar with Python, I suggest starting with:

https://github.com/kuleshov/cs228-material/blob/master/tutorials/python/cs228-python-tutorial.ipynb

## Local Installation Instructions

1) Install Python 2.7

2) Install pip

3) Simply download the requirements.txt file to your local computer and run:
`pip install -r requirements.txt`

## (Beta) Binder installation Instructions

Mybinder.org is a new initiative to allow people to run Jupyter notebooks
on the web. A binder is set up at:
https://mybinder.org/v2/gh/vr140/intro-deep-learning/master

NOTE: The binder is still in beta and may not work. For the most reliable environment,
please see "Local Installation Instructions" above.

## AWS Installation Instructions

1) Follow instructions in https://medium.com/@DJVJallday/a-how-to-on-deep-reinforcement-learning-setup-aws-with-keras-tensorflow-openai-gym-and-jupyter-88bc0cc67e02  

NOTE: You can skip the testing of OpenAI in step 20. This is only needed for reinforcement learning.

2) After completing all the installation instructions, do the optional instructions noted on the page:

`sudo apt-get install libcupti-dev`  # needed for tensorflow
`sudo pip install -U tensorflow`   # Python 2.7 (for python3 instructions, see https://www.tensorflow.org/install/install_linux#InstallingNativePip)

3) Use pip list to show the packages installed on the system. Validate the install and test the version:

python -c "import tensorflow as tf; print(tf.__version__)"
# you should see version x.y.z
