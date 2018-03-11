# Deep Learning

# I] How to install Keras with a TensorFlow backend for deep learning
## 1. Setting up Anaconda

Anaconda is a free and open-source software distribution for data science. In a nutshell, it's an up-to-date, comprehensive bundle of the most popular tools and libraries in this field and enables you to dive in quickly and easily.

Of course, you could use [pip](https://pip.pypa.io/en/stable/). Python's default package manager, to install these libraries but that would likely take a while considering there are [hundreds](https://pypi.python.org/pypi?%3Aaction=browse) to choose from. In addition, newcomers typically don't know which libraries are useful and which are optional. Most importantly, a library may build off another library (the latter is called a dependency), so it's crucial to install them in the correct order and use the appropriate version of each one to ensure all libraries play nicely.

Fortunately, Anaconda takes these responsibilities off your shoulder. First, the installer comes with the core libraries for data science to get you up and running immediately. In addition, Anaconda includes a language-agnostic package manager called [conda](https://conda.io/docs/intro.html) that enables you to add more libraries later.

As the cherry on top, conda is also a top-notch virtual environment manager, so you don't need virtualenv or venv. For those new to virtual environments, think of them as tools to keep dependencies used by different projects or tasks in separate locations to avoid potentially messy conflicts. Later in this tutorial, we'll create a conda environment for our deep learning tasks.

To get started, download [Anaconda](https://www.continuum.io/downloads) with the latest version of Python—don't worry, you can always create a conda environment that uses an older version if needed. The installation will take a few minutes so grab a coffee!


