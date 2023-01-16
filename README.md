### Table of Contents

1. [Introduction](#intro)
2. [Folder Descriptions](#files)
3. [Results](#results)
4. [Installation](#installation)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Introduction<a name="intro"></a>

As part of [Udacity nanodegree](https://www.udacity.com/course/data-scientist-nanodegree--nd025?utm_source=gsem_brand&utm_medium=ads_r&utm_campaign=19167921312_c_individuals&utm_term=143524484639&utm_keyword=udacity%20data%20science_p&gclid=Cj0KCQiA5NSdBhDfARIsALzs2EAHpUX_4D3aZrBcu_PbklsCJYBWFEupJ-i6mpiKLVpCNy_7u8hDLVoaAje4EALw_wcB), we got an assignment to apply data science princliples to a dataset. As a health and fitness enthusiast I tool this opportunity to explore some health and fitness data and see how age and gender might affect athletic performance. 

My specific questions I wanted to explore were the following:

1. What percentage of participants had a healthy bmi score?
2.
3.


1. How other developers suggested breaking into the field (what education to pursue)?
2. What factors about an individual contributed to salary?
3. How bias played a role in the suggestions of developers for how to break into the field?
4. What was the state of bootcamps for assisting individuals with breaking into developer roles?
5. How were bootcamps assisting with increasing diversity in tech careers?

The full set of files related to this course are owned by Udacity, so they are not publicly available here.  However, you can see pieces of the analysis here.  This README also serves as a template for students to follow in creating their own project README files.


## Folder Descriptions <a name="files"></a>

Please see below a description of each of the folders of interest. The remaining folders are part of the environment setup only.
                                       
- data: Contains original and preprocessed datasets.          
- notebooks: There are three notebooks that flow in order. They start from having a quick exploration of the data, processing the data and finally having a deep dive in to analysing the data.  

## Results<a name="results"></a>

The main findings from the analysis can be found in the [analysis notebook](notebooks/2_Analysis.ipynb) and the post available on [Medium](https://medium.com/@josh_2774/how-do-you-become-a-developer-5ef1c1c68711).

## Installation <a name="installation"></a>

This project uses remote development through [Windows Subsystem for Linux 2](https://docs.microsoft.com/en-us/windows/wsl/install), or running natively from Windows. The environment is controlled using `venv` and `pip` for package management.

In order to get the project up and running, open a terminal window and run the following commands:

```
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

The data was obtained from [Kaggle](https://www.kaggle.com/datasets/kukuroo3/body-performance-data).
