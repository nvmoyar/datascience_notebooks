## Descriptive Statistics with Python

The purpose of this repo is to introduce some simple tasks about data manipulation and visualizations, with Python and its libraries and packages Numpy, Pandas, MatPlotlib and Scikit-Learn. All these Jupyter Notebooks are taken as notes from [Datacamp's Data Analyst track](https://www.datacamp.com/tracks/data-analyst-with-python) exercises. During my journey through Udacity Deep Learning and Artificial Intelligence Engineer Nanodegrees, I found that besides struggling with neural architectures, tuning, statistical models, calculus and algebra needed to understand in order to build and train any model, I needed to be fluent manipulating data since data pre-process is usually needed before feeding your model. These notebooks are not an attempt at teaching Data Analysis to anyone. These notebooks just cover some routinary tasks in Python. Each notebook is named after its Datacamp's analogous course. 

[DataCamp](https://www.datacamp.com) is a time flexible, online data science learning platform offering tutorials and courses in data science. Students can master data analysis from the comfort of their browser, at their own pace, and tailored to their needs and expertise. These Data Analyst courses are also available in R. The learning experience is really fast since you do not need to install anything and from the very beginning, you are encouraged to focus only in coding and learn to code, thus, your goal.  

Since some people have asked me similar questions, I point some references here if you need some refresher courses in Statistics: 

[ProbStat by Stanford Lagunita](https://lagunita.stanford.edu/courses/course-v1:OLI+ProbStat+Open_Jan2017/about) -> Awesome hands-on course, no programming experience needed. Udacity offers ud827, which is ok as well. 

[Statistical thinking in Python I](https://www.datacamp.com/courses/statistical-thinking-in-python-part-1) and [Statistical thinking in Python II](https://www.datacamp.com/courses/statistical-thinking-in-python-part-2) -> Awesome courses from Justin Bois offered by Datacamp. You go through EDA and CDA, concept by concept and exercise by exercise. Some experience manipulating data frames is needed. 

A month ago on March 30th, 2018, Rachael Tatman from Kaggle, run a nice set of tutorials to be performed in 5 days -one day each, but now it is over, you can do it at your pace-, related to how to deal with ordinary operations like scaling and normalizing your data, dealing with time series, data inconsistencies, missing data, etc. If you do not have yet a Kaggle profile, this could be your chance by forking her notebook and start working without installing anything. [Data Cleaning Challenge](https://www.kaggle.com/rtatman/data-cleaning-challenge-handling-missing-values).

## Contents

* [Introduction to Databases in Python](Introduction_to_Databases_in_Python.ipynb) -> Connecting and manipulating databases from a Python client. 

* [Introduction_to_Data_Visualization and customizing plots](Introduction_to_Data_Visualization.ipynb) -> Customize your plots

* [Manipulating Dataframes](Manipulating_DataFrames_with_Pandas.ipynb) -> Transform, extract, and filter data from DataFrames, Work with pandas indexes and hierarchical indexes, Reshape and restructure your data. Cleaning data. 

* [Merging Dataframes with Pandas](Merging_DataFrames_with_pandas.ipynb) -> Merge data: one-to-one, one-to-many, many-to-many. 

* [Statistical Thinking in Python](Statistical_Thinking_in_Python_I.ipynb) -> EDA -Exploratory Data Analysis-

* [Statistical Thinking in Python II](Statistical_Thinking_in_Python_II.ipynb) -> Inference statistics, Pearson Correlation, Hypothesis testing, Test statistics and p-values, and case study through all these. 

* [Supervised Learning with Scikit-learn](Supervised_Learning_with_scikit-learn.ipynb) -> Regression and classification problems, error functions and regularization. 

* [Introduction to Natural Language Processing with NLTK](Natural_Language_Processing_Fundamentals.ipynb) - [NLTK](https://www.nltk.org) is a leading platform for building Python programs to work with human language data. This notebook covers different of words tokenization. This notebook does not contain the 100% contents of its [analogous course](https://www.datacamp.com/courses/natural-language-processing-fundamentals-in-python)

## Requirements and environment

These are the packages you will need in your environment in order to run these notebooks. You are free to use [https://conda.io/docs/](https://conda.io/docs/) or whatever you feel comfortable with, of course. 

name: data-analytics
channels:
- anaconda
- defaults
dependencies:
- matplotlib=2.1.1
- jupyter=1.0.0
- nb_conda=2.2*
- pandas=0.22.0
- python=3.5.4
- scikit-learn=0.19.1
- scipy=1.0.0
