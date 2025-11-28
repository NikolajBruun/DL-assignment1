# Deep Learning Assignment 1

## Files
- DL_Backpropagation_pen_and_paper.ipynb - Solution for question in task 1 answered in the notebook.
- DL_AutoDiff_Nanograd.ipynb - Solution for question in task 2 answered in the notebook.
- feedforwardAssignment.ipynb - Solution for Task 3 and 4
- requirements.txt - packages that needs to be installed before running any code.

Before running any code make sure to install the requirements.

Note that the code already has been run, so the outputs will already show. However, if you want to run the code again do as follows:

Note that when running the feedforwardAssignment.ipynb file you might be asked for a Wandb API key.

The code can be run by opening the jupyter notebook files listed above and run it.
If you want to run the code from the terminal you should convert the files to a python script:
jupyter nbconvert --to script DL_Backpropagation_pen_and_paper.ipynb   
jupyter nbconvert --to script DL_AutoDiff_Nanograd.ipynb 
jupyter nbconvert --to script feedforwardAssignment.ipynb   


And then run the script:
python DL_Backpropagation_pen_and_paper.py
python DL_AutoDiff_Nanograd.py 
python feedforwardAssignment.py 
