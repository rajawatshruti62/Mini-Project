# Mini-Project
Emotion detection system:

Introduction:
Our project aims to identify anyone's emotion and to categorize them into one of the seven categories- angry, disgusted, fearful, happy, neutral, sad and surprised.
Here we are going to Deep Convolutional Neural Networks.

Dependencies:
For this we need to install the following software:
1)Python  3 
2)Numpy
3)Open CV
4)Tensorflow

Basic Usage:
In order to use this project,first of all you need to install all the dependencies on your device.
Here in order to make the work simpler we will be installing the requirement using pip installation.
We'll use `tensorflow-2.0` and make use of the Keras API using the `tensorflow.keras` library.

Method of installation:

Python Installation:

1)On the web browser, in the official site of python (www.python.org), move to the Download for Windows section.
2)All the available versions of Python will be listed. Select the version required by you and click on Download. Choose the installer which suits your system operating system and download the instlaller.
3)We downloaded the Python 3.9.1 Windows 64 bit installer.Run the installer. Make sure to select both the checkboxes at the bottom and then click Install New.
4)On clicking the Install Now, The installation process starts.
5)The installation process will take few minutes to complete and once the installation is successful, the following screen is displayed.
Verifying Python Installation
6)To ensure if Python is succesfully installed on your system. Follow the given steps −
a)Open the command prompt.
b)Type ‘python’ and press enter.
c)The version of the python which you have installed will be displayed if the python is successfully installed on your windows.
Verifying PIP Installation
7)Open the command prompt.
8)Enter pip –V to check if pip was installed.
9)The following output appears if pip is installed successfully.

Creating virtual environment:

First of all you need to install the requirement in the virtual environment.Virtual Environment should be used whenever you work on any Python based project. It is generally good to have one new virtual environment for every Python based project you work on. So the dependencies of every project are isolated from the system and each other.We use a module named virtualenv which is a tool to create isolated Python environments. virtualenv creates a folder which contains all the necessary executables to use the packages that a Python project would need.
1)Open your command prompt(type cmd in your run terminal). Now go to the directory path(location), where you want to install the virtual environment.
2)Now type the command:
pip install virtualenv
3)Installation process begins
4)Test your installation using command:
virtualenv --version
5)Using virtualenv module,you can create a virtualenv using the following command:
virtualenv my_name
6)After running this command, a directory named my_name will be created. This is the directory which contains all the necessary executables to use the packages that a Python project would need. This is where Python packages will be installed.
If you want to specify Python interpreter of your choice, for example Python 3, it can be done using the following command:
virtualenv -p /usr/bin/python3 virtualenv_name
(location can be user dependent or where you want to create the project)
6)Now after creating virtual environment, you need to activate it. Remember to activate the relevant virtual environment every time you work on the project. This can be done using the following command:
source virtualenv_name/bin/activate

here you go to use your virtual environment.

From now onwards, for any installation we will firstly activate the virtual environment created.
Installation Of Numpy:

Then install the numpy library using the following command:
pip install numpy
Installation will begin.
To check use command:
pip show numpy

Installation of open CV:

To Install the Current Latest version of OpenCV then use the below commands:

Use this Command:

pip install --upgrade opencv-python

If you're facing problem in above command then try this :
pip install --upgrade opencv-contrib-python

To check the version of installed OpenCV:
import cv2
print(cv2.__version__)

Installation of Tensorflow:

For this run the following command:
pip install --upgrade pip
Then, install TensorFlow with pip.
Note: Do not install TensorFlow with conda. It may not have the latest stable version. pip is recommended since TensorFlow is only officially released to PyPI.
Command for installation: pip install tensorflow

With this your device acquired all dependencies to run our project.




