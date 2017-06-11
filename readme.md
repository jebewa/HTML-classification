# Code instructions
In this Jupyter Notebook you can find my solution to the second project for the course *Introduction to Data Mining*.
This Notebook contains both the code and the report.

## Loading the Data
In order to load the required data into this Notebook, the Notebook needs to be placed in the same directory
as two folders with the name **train** and **test**. Inside the **train** folder there should be three subfolders:
**course**, **faculty** and **student**. These three subfolders should contain the HTML-files for respectively
the course webpages, the faculty webpages and the student webpages.

The **test** folder is where all the test data needs to be stored.

## Installing the libraries
This Notebook is written in Python 2.7 and requires some non-standard libraries. If these libraries are not
installed on your machine, some cells of code will give errors. Below is a list of required libraries.

- NLTK
- Matplotlib
- Scipy
- Numpy
- Sklearn
- Pandas
- Time
- Bs4

In feature engineering section, the stopword list from Python's NLTK will need to be downloaded. The command for downloading this list is already included in the code. This command will however need to be uncommented first.
