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
You also will need to add a folder named Financial_News and unzip the datasets you retrieve from kaggle https://www.kaggle.com/datasets/miguelaenlle/massive-stock-news-analysis-db-for-nlpbacktests

![image](https://github.com/r0704067/ML-with-financial-data-vs-ML-with-combined-financial-and-news-sentiment-data/assets/57663262/083a5437-e579-4ed5-9d54-44effefc21c6)

### 3. Open the Project Folder
In VS Code, go to File and choose Open Folder:

Open the project folder

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

### 6. Using venv in VSCode
Python’s preferred way to use virtual environments, is via ‘venv’. It allows you to manage separate package installations for different projects. It essentially allows you to create a “virtual” isolated Python installation and install packages into that virtual installation. 

When you switch projects, you can simply create a new virtual environment and not have to worry about breaking the packages installed in the other environments. It is always recommended to use a virtual environment while developing Python applications.

To create a virtual environment, open up a terminal window in VSCode (Menu > Terminal > New Terminal). It will open up in your folder. Execute the command 

py -m venv ML_env

VSCode will detect that you’ve created a new virtual environment, and will ask you if you want to select it for the workspace folder. Hit Yes. 

![image](https://github.com/r0704067/ML-with-financial-data-vs-ML-with-combined-financial-and-news-sentiment-data/assets/57663262/3bc30d23-9e21-4d12-8715-d4136cb0b5da)

Notice in your directory, that a new folder is created ML_env.

### 6. Activating venv in VSCode
Next, we need to activate this virtual container as our Python environment to use. 

### 6.1 Activating the environment in the IDE
This pretty straightforward. Go to the top right corner, where you can select your interpreter
 
 ![image](https://github.com/r0704067/ML-with-financial-data-vs-ML-with-combined-financial-and-news-sentiment-data/assets/57663262/9b8381a9-98fd-4c59-9837-ab344b1f2431)

and select the ML_env

