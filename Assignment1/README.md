# Welcome to Assignment 1!

We'll be using Python throughout the course. If you've got a good Python setup already, great! But make sure that it is at least Python version 3.8. If not, the easiest thing to do is to make sure you have at least 3GB free on your computer and then to head over to (https://www.anaconda.com/download/) and install the Python 3 version of Anaconda. It will work on any operating system.

After you have installed conda, close any open terminals you might have. Then open a new terminal and run the following command:

## 1. Create an environment with dependencies specified in env.yml:
    conda env create -f env.yml

## 2. Activate the new environment:
    conda activate assignment1
    
## 3. Inside the new environment, install IPython kernel so we can use this environment in jupyter notebook: 
 
    python -m ipykernel install --user --name assignment1


## 4. Homework 1 (only) is a Jupyter Notebook. With the above done you should be able to get underway by typing:

    jupyter notebook exploring_word_vectors.ipynb

## To deactivate an active environment, use
    conda deactivate
