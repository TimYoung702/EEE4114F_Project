# EEE4114F_Project

This README will explain how to use the Jupyter Notebook for Image Classification of single digits.
A requirement for this is you have to have anaconda installed.

Firstly clone the git reposatory, Then move the ML_Environment.yml to wherever you store your anaconda environments
Open anaconda and then navigate to your enviromnets folder. 
You then install this environment using the command: >conda env create -f ML_Environment.yml
Once then environment is installed anaconda will tell you how to activate the environment
Activate the environment and then navigate to the cloned reposatory
Use the command >jupyter notebook
This will open jupyter and allow you to open the MNIST_Classification.ipynb file
Once the file is open, click on Cell and click on Run All this will create and train the CNN
To test the CNN with either our hand-drawn images or your own, go to the last cell and change the file name in the first line
The naming convention for out data is the number spelled followed by a dash followed by a number from 1 to 5
For Example : four_2.png
If you want to test your own data, the only requirement is that the number be white on a blakc background.
Then to test your data, just run the individual cell, don't click run all again or that wil recreate the CNN

That is all hopefully you enjoy using the CNN