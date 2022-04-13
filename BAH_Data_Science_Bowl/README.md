# BAH_Data_Science_Bowl

This is a collaboration in neural networks, machine learning, and image recognition.
We are learning these topics over winter break as something fun to do,
and put it on github so we can collaborate while separate.

Some other places to check out:  
http://opencv.org/documentation.html  
http://deeplearning.net/tutorial/  

Most images I have used up until now are found in ImageSets/ and include the Yale Face Database.
http://vision.ucsd.edu/content/yale-face-database

To install all the packages I have DL'd for Python, use:  
$ source env/bin/activate  
$ pip install -r requirements.txt  

If any required packages are changed, use:
$ pip freeze >> requirements.txt

See requirements.txt for current versions, but as for usage,
the libraries installed for this project are (keep in mind, some are dead ends):
# Tools to facilitate quicker Python code:
numpy                                 # Faster implementation for numerical analysis  
scipy                                 # Scientific Python (another library to facilitate quick calculation)  
https://github.com/Theano/Theano      # Facilitates quicker tools for work with matrices (CV requires linear algebra)  
idx2numpy                             # Converting idx filetypes to numpy arrays (12/27: dead end)  
matplotlib                            # Graphing and plotting  
# Brunt of the work done by (probably?):
nolearn                               # Utility modules helpful in machine learning: works well with scikit  
Pillow                                # Active fork of Python Image Library  
scikit-learn                          # Extensive library for work in machine learning  
# Not sure what these do (lost track):
funcsigs  
joblib  
https://github.com/Lasagne/Lasagne  
mock  
nose  
pbr  
pyparsing  
python-dateutil  
pytz  
six  
tabulate  
wheel  
