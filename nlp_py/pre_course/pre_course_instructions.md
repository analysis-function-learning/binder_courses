# Pre Course Instructions

In order to complete the course you will need to install the packages used in the course.

If you do not have the correct versions of packages, you will likely be unable to run all of the code in the course.

The pacakges needed for this course were the most up to date when this course was created, which are likely not the ones you have on your machine.

Please follow the instructions below to ensure you can complete the course.

There are broadly 3 ways to get the required packages:

* Overwrite your existing packages by manually installing packages one by one
  * will potentially stop other projects you are working on work
* Overwrite your existing packages by installing all dependencies using `requirements.txt`
  * will potentially stop other projects you are working on work
* Creating a new package environment and installing packages there **(Recommended)**
  * will not affect other installed packages
  
You will need to make sure you can install packages on your device before completing these pre-course instructions.

## Installing All Packages - Overwriting Existing Packages

Within this folder there is a file called `requirements.txt`.

This text file contains every package, it's dependencies and version number required to complete this course.

First - shut down your Jupyter Notebook completely. There should be no Jupyter Notebook windows open. 

To install the packages you will use the following commands in your command line interpreter (such as "Anaconda Prompt").

You will need to navigate your command line to the root of the download folder for this course. This will ensure that your
notebooks can be found when launching Jupyter.

Depending on your working directory, where your prompt is looking, you may need to add a path to the `requirements.txt` file.



```sh
>pip install -r requirements.txt
```

Your computer will then install all of the packages required for this course - it will take a few minutes to complete.

Re-open your Jupyter Notebook and start working through the course.

For awareness, and in case you wish to install packages individually you will need:

*  matplotlib==3.3.3
*  nltk==3.5
*  numpy==1.19.5
*  pandas==1.1.5
*  spacy==3.1.0
*  wordcloud==1.8.1
*  scikit-learn==0.24.1
*  scipy==1.5.4

## Virtual Environment Kernel - Not overwriting existing packages (recommended)

If alternatively, you would like to set up a virtual environment kernel for Jupyter Notebook, read the instructions within `/pre_course/venv.html`.

The reasons for electing to use a virtual environment for this course include:

* It prevent losing your original packages from other projects
* It improves the reproducibility of your work

The best place to initialise the venv will be in the downloaded folder in this course (at the same level as `\data\` and `\notebooks`. Therefore all .ipynb files will be discoverable from Jupyter.

**NOTE** You will need to select the correct kernel - the one you have created using `venv` in each notebook run.
