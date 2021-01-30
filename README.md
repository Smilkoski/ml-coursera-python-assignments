# [Coursera Machine Learning MOOC by Andrew Ng](https://www.coursera.org/learn/machine-learning) 
# Python Programming Assignments

![](machinelearning.jpg)

This repositry contains the python versions of the programming assignments for the [Machine Learning online class](https://www.coursera.org/learn/machine-learning) taught by Professor Andrew Ng. This is perhaps the most popular introductory online machine learning class. In addition to being popular, it is also one of the best Machine learning classes any interested student can take to get started with machine learning. An unfortunate aspect of this class is that the programming assignments are in MATLAB or OCTAVE, probably because this class was made before python became the go-to language in machine learning.

The Python machine learning ecosystem has grown exponentially in the past few years, and is still gaining momentum. I suspect that many students who want to get started with their machine learning journey would like to start it with Python also. It is for those reasons I have decided to re-write all the programming assignments in Python, so students can get acquainted with its ecosystem from the start of their learning journey. 

These assignments work seamlessly with the class and do not require any of the materials published in the MATLAB assignments. Here are some new and useful features for these sets of assignments: 

- The assignments use [Jupyter Notebook](http://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/what_is_jupyter.html), which provides an intuitive flow easier than the original MATLAB/OCTAVE assignments.
- The original assignment instructions have been completely re-written and the parts which used to reference MATLAB/OCTAVE functionality have been changed to reference its `python` counterpart.
- The re-written instructions are now embedded within the Jupyter Notebook along with the `python` starter code. For each assignment, all work is done solely within the notebook.
- The `python` assignments can be submitted for grading. They were tested to work perfectly well with the original Coursera grader that is currently used to grade the MATLAB/OCTAVE versions of the assignments. 
- After each part of a given assignment, the Jupyter Notebook contains a cell which prompts the user for submitting the current part of the assignment for grading.  

## Downloading the Assignments

To get started, you can start by either downloading a zip file of these assignments by clicking on the `Clone or download` button. If you have `git` installed on your system, you can clone this repository using : 

    clone https://github.com/Smilkoski/ml-coursera-python-assignments.git
    
Each assignment is contained in a separate folder. For example, assignment 1 is contained within the folder `Exercise1`. Each folder contains two files: 
 - The assignment `jupyter` notebook, which has a `.ipynb` extension. All the code which you need to write will be written within this notebook.
 - A python module `utils.py` which contains some helper functions needed for the assignment. Functions within the `utils` module are called from the python notebook. You do not need to modify or add any code to this file.
