# Machine-Learning-and-Statistics-Tasks

### Author: Babu Baskaran(G00376292@gmit.ie)

####  Repository : GitHub

Machine Learning and Statistics module.  This repository contains one single jupyter notebook called ML AND S TASK.ipynb which contain my solutions to the 4 task assigned of this semster.  Each task is contained within its own section of the notebook with all the reference links.

#### How To download the Repository

* Go to GitHub.
* Go to my repository: GitHub
* Click the code button which is colored green
* Click on HTTPS and copy the link that is shown.
* Open the command line on your machine, navigate to the directory where you would like to clone the repository down to.
* Enter the command : git clone followed by the URL of the repository.
* The repository will be cloned down to your current working directory.
* You will need to navigate to this folder location on the command line in order to run the program.

#### How to run jupyter notebook

* On the command line go to the folder where the repository has been maped.
* Type jupyter notebook on the command line and press enter
* After few seconds jupyter notebook will open in the default browser.
* Open the ML AND S TASK.ipynb notebook in the browse.
* To run the code press the shift key and press enter and output will be displayed on the next row.

## Task 1

Write a Python function called sqrt2 that calculates and
prints to the screen the square root of 2 to 100 decimal places. Your code should
not depend on any module from the standard library1 or otherwise. You should
research the task first and include references and a description of your algorithm.

## Task 2

The Chi-squared test for independence is a statistical
hypothesis test like a t-test. It is used to analyse whether two categorical variables
are independent. The Wikipedia article gives the table below as an example [4],
stating the Chi-squared value based on it is approximately 24.6. Use scipy.stats
to verify this value and calculate the associated p value. You should include a short
note with references justifying your analysis in a markdown cell.

## Task 3

The standard deviation of an array of numbers x is
calculated using numpy as np.sqrt(np.sum((x - np.mean(x))**2)/len(x)).
However, Microsoft Excel has two different versions of the standard deviation
calculation, STDEV.P and STDEV.S . The STDEV.P function performs the above
calculation but in the STDEV.S calculation the division is by len(x)-1 rather
than len(x) . Research these Excel functions, writing a note in a Markdown cell
about the difference between them. Then use numpy to perform a simulation
demonstrating that the STDEV.S calculation is a better estimate for the standard
deviation of a population when performed on a sample. Note that part of this task
is to figure out the terminology in the previous sentence.