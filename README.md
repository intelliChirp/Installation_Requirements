# Installation_Requirements
requirements.txt - Use this to install all the packages needed to run SNAW

## How to Install Needed Packages for SNAW Web, Snaw Offline, and SNAW Neural Network

Setting Up a Python Virtual Environment with all Needed Python Packages
Note: Anaconda is not compatible for this prerequisite.

1. Install Python (version 3.7.4) from:
https://www.python.org/downloads/release/python-374/
2. Make sure Pip is up-to-date. Run command:
~~~~
py -m pip install --upgrade pip
~~~~
3. Navigate to the directory where you would like to install the virtual environment.
4. Run command py -m venv snaw (change ‘snaw’ to what you would like to name the virtual environment).
5. Activate the environment by navigating to the file directory of your environment and running command:
~~~~
.\Scripts\activate
~~~~
6. Verify that the virtual environment is running by looking on the left hand side of the bottom line. You should see the name of your virtual environment in parenthesis (Ex: (snaw) C:\......)
7. Visit SNAW’s ‘Installation_Requirements’ repository at:
https://github.com/intelliChirp/Installation_Requirements
8. Click the green ‘Clone or download’ button.
9. Click on ‘Download ZIP’
10. Copy requirements.txt file to your virtual environment directory.
11. Navigate to your virtual environment’s directory.
12. Type the command:
~~~~
pip install -r requirements.txt
~~~~
13. Wait for the packages to install on your local machine.
14. Done! 

If you ran into trouble during the virtual environment setup, this website may be helpful:
(https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/)

