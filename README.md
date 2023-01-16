
### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python.  The code should run with no issues using Python versions 3.*.

## Project Motivation<a name="motivation"></a>

For this project, I was interestested in using Stack Overflow data from 2017 to better understand:

1. How other developers suggested breaking into the field (what education to pursue)?
2. What factors about an individual contributed to salary?
3. How bias played a role in the suggestions of developers for how to break into the field?
4. What was the state of bootcamps for assisting individuals with breaking into developer roles?
5. How were bootcamps assisting with increasing diversity in tech careers?

The full set of files related to this course are owned by Udacity, so they are not publicly available here.  However, you can see pieces of the analysis here.  This README also serves as a template for students to follow in creating their own project README files.


## File Descriptions <a name="files"></a>

There are 3 notebooks available here to showcase work related to the above questions.  Each of the notebooks is exploratory in searching through the data pertaining to the questions showcased by the notebook title.  Markdown cells were used to assist in walking through the thought process for individual steps.  

There is an additional `.py` file that runs the necessary code to obtain the final model used to predict salary.

## Results<a name="results"></a>

The main findings of the code can be found at the post available [here](https://medium.com/@josh_2774/how-do-you-become-a-developer-5ef1c1c68711).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to Stack Overflow for the data.  You can find the Licensing for the data and other descriptive information at the Kaggle link available [here](https://www.kaggle.com/stackoverflow/so-survey-2017/data).  Otherwise, feel free to use the code here as you would like! 






***

# Introduction 
Give an introduction to purpose.

# Project Folders
Please see below a description of each of the folders of interest. The remaining folders are part of the environment setup only.

### Functional                                                   
- evc_functions:  
- tests: Testing functionality.                        

### Other                                               
- data: Contains original and transformed datasets including once off transformation notebook.          
- analysis: Analysis notebooks used for exploration and testing only.                                       


# Getting Started
This project uses remote development through [Windows Subsystem for Linux 2](https://docs.microsoft.com/en-us/windows/wsl/install), or running natively from Windows. The environment is controlled using `venv` and `pip` for package management.

## Installation process
In order to get the project up and running, open a terminal window and run the following commands:

```
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

## Testing
Pytest is used to run the tests. Ensure the `vscode` testing extension is linked to pytest. 




A README.md file that communicates the libraries used, the motivation for the project, the files in the repository with a small description of each, a summary of the results of the analysis, and necessary acknowledgments.
Your code in a Jupyter notebook, with appropriate comments, analysis, and documentation.
You may also provide any other necessary documentation you find necessary.
For the blog post, pick a platform of your own choice. For example, it can be on your website, a Medium post (Josh's sample report on How Do YOU Become A Developer?), or a Github blog post. Your blog must provide the following:




# Introduction 
The Data Analytics (DA) Studies group is exploring the use of [Descartes Labs](https://www.descarteslabs.com/) as a software and/or data layer for satellite image processing pipelines.

# Getting Started

The notebooks will run in Descartes Labs [workbench](https://workbench.descarteslabs.com), 
which is an example of a cloud hosted [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/). 

If you are new to Descartes Labs then start with the **1_introduction** folder and
work you way from there in order.

# Local Installation

To run this code locally you will need to install the dependencies. The official [Descartes Labs installation guide](https://docs.descarteslabs.com/installation.html) suggests using conda and pip.

You can install conda from [here](https://docs.conda.io/en/latest/miniconda.html).

Create a new python 3.8 virtual environment.

`conda create -n my_env python=3.8`

To activate this environment in Windows 

`activate my_env`

The following order is important. First install these packages using conda

`conda install shapely matplotlib`

Then install these packages using pip.

`pip install descarteslabs nbstripout`

Hopefully that all went well 🤞

If so, you are all set
