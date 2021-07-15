# Introduction to Python

Welcome to **Introduction to Python**! Python is one of the most popular and powerful programming languages. It is used extensively in computational and data science, and you will use it in almost all modules during your MSc studies. Therefore, you need to familiarise yourself with Python before your MSc journey.

## How to run this course

There are three possibilities for how you can learn Python with our self-guided course. **JupyterHub** and **Binder** options allow you to run tutorials in the cloud - you do not need to install anything, and no files will be created on your machine. All you need is a web browser and internet connection. However, you need to download Jupyter notebooks you worked in to ensure your work is not lost at the end of each session. The third option is to create a small Python environment and run all tutorials on your machine. There is no difference in what you will learn, and we give you complete freedom to choose how you want to run tutorials.

### 1. JupyterHub

1. **Create a GitHub account**. In the email you received, we sent you the unique username we generated for you. Create a GitHub account and make sure your GitHub account uses that username.

2. **Login to JupyterHub**. On the following link, you can access our JupyterHub server and log in using the GitHub account you just created. After login, it may take some time for JupyterHub to start, so please be patient.

JUPYTERHUB_LINK

**IMPORTANT:** Please note that we do guarantee your work is backed up. Therefore, we strongly recommend downloading the notebook at the end of each session.

### 2. Binder

You can access Binder by clicking on the following *Binder badge*:

BINDER_BADGE

**IMPORTANT:** Please note that after the Binder session ends, all your work is deleted. Therefore, please download the notebook you worked in at the end of each session.

### 3. On your machine

1. **Install Git**. Please follow installation instructions for your operating system on [Git webpage](https://git-scm.com/).

2. **Clone repository**. In Terminal (Linux and MacOS) or Command Prompt (Windows), navigate to the location where you want the course files to be and run
```
$ git clone https://....
```    
3. **Install Anaconda**. We recommend installation using conda package manager. If you do not already have it installed, download [Anaconda](https://www.anaconda.com/products/individual) Python 3 for your operating system and follow the instructions to install it. After the installation is complete, in Terminal (Linux and MacOS) or Anaconda Prompt (Windows), navigate to the course directory, create a new conda environment, and activate it using:
```
$ cd path/to/course/directory
$ conda env create -f environment.yml
$ conda activate intro-to-python
``` 
    
4. **Open Jupyter Notebook**. In the environment you just activated, run:
```
$ jupyter notebook &
```

## Support

If you require support, have questions, want to report a bug, or want to suggest an improvement, please raise an issue in the course repository.