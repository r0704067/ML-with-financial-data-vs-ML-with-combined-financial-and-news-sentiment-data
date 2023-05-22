# ML-with-financial-data-vs-ML-with-combined-financial-and-news-sentiment-data
In this README I'll explain the installation process of VS Code, Python and Jupyter.
### 1. Install the Python extension for VS Code and Python
First install Visual Studio Code, if it is not already on your machine.

![image](https://github.com/r0704067/ML-with-financial-data-vs-ML-with-combined-financial-and-news-sentiment-data/assets/57663262/ab2fa00d-cf60-4c3a-9b3b-5e21f6dfbb78)

Next, install the Python extension for VS Code from the Visual Studio Marketplace. Open VS Code and click the Extensions icon in the Activity Bar on the side of VS Code. Search for Python and install the Python extension (it is named Python and it's published by Microsoft). It's probably the first in the list:

![image](https://github.com/r0704067/ML-with-financial-data-vs-ML-with-combined-financial-and-news-sentiment-data/assets/57663262/8f01311b-4394-4929-afe8-56023f1e3084)

Click the Install button.

Along with the Python extension, you need of course to install Python as well, if it is not already on your device. Go to python.org/downloads and use the Download Python button that appears first on the page to download the latest version:

![image](https://github.com/r0704067/ML-with-financial-data-vs-ML-with-combined-financial-and-news-sentiment-data/assets/57663262/f37011b4-9230-4bb1-9766-68214cd1a207)
 
To verify that you've installed Python successfully on your machine, open a command prompt and run the following command:

py -3 --version

You should see something like

Python 3.10.7

### 2. Download the repository
First create a folder where you can save all the files from this repository. In this folder you can git clone the repository or unzip the downloaded repository.

### 3. Open the Project Folder
In VS Code, go to File and choose Open Folder:

### 4. Select a Python Interpreter
Python is an interpreted language, and in order to run Python code and get Python IntelliSense, you must tell VS Code which interpreter to use.

From within VS Code, select the Python 3 interpreter by opening the Command Palette (Ctrl+Shift+P), start typing the Python: Select Interpreter command to search:

![image](https://github.com/r0704067/ML-with-financial-data-vs-ML-with-combined-financial-and-news-sentiment-data/assets/57663262/a0954927-c74b-47d0-b21b-d2f7e7384fb1)

Then select the command and choose the Python environment you've just installed:

![image](https://github.com/r0704067/ML-with-financial-data-vs-ML-with-combined-financial-and-news-sentiment-data/assets/57663262/ff01cfda-31d4-4415-8aa1-275382f3fc8f)

### 5. Installing the IPython Kernel
The IPython Kernel is the Python execution backend for Jupyter. This one needs to be installed before you can execute Jupyter Notebooks code blocks in VS Code.

Open a new Terminal Window in VS Code and install the IPython Kernel:

py -m pip install ipykernel

If you get a warning about the Python Scripts folder not being included in the PATH environment variable, add it using the System|Advanced System Configuration.
