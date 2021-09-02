# Distributions python package

A Python module is just a Python file containing code. A package is a collection of Python modules. The distribution and Gaussian code are refactored into individual modules and the to a python package. I used pip to install a Python package from a local folder on my computer.

The package contains :
* setup.py file, which is required in order to use pip install.
* A subfolder called distributions, which is the name of the Python package.
Inside the distributions folder, there are:
 * The Gaussiandistribution.py file (provided).
 * The Generaldistribution.py file (provided).
* The __init__.py file.

After downloading the package and unzipping it, use your terminal window to navigate into the python_package folder.

Enter the following:

```
cd 3a_python_package

pip install
```
If everything is set up correctly, pip installs the distributions package into the workspace. You can then start the Python interpreter from the terminal by entering:

```
python
```
Then, within the Python interpreter, you can use the distributions package by entering the following:
```

from distributions import Gaussian

gaussian_one = Gaussian(25, 2)

gaussian_one.mean

gaussian_one + gaussian_one
```
In other words, you can import and use the Gaussian class because the distributions package is now officially installed as part of your Python installation.
