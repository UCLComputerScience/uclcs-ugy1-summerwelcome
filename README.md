# Welcome to UCL Computer Science!
Here you will find a number of self-study activities created for incoming Undergraduate Computer Science students at UCL. 

The first is an introduction to Data Visualisation. Its purpose is to give you some insight into one of the many ways that the skills you will learn on your undergraduate course can be used in 'real' life.

The second is an introduction to Algorithms. The purpose of this activity is to give you some first insights into one of the fundamental topics you will learn during your first year undergraduate degree programme (COMP0005 - Algorithms).

While you could do the activities in any order, if you have never used Jupyter or Python you might find it easier to start with the data visualisation activity.

## Getting started
These activities use a cloud service Jupyter notebook.

When you open one of the following links, the cloud service creates a virtual coding environment in the cloud for you to use so you don't need to install anything on your machine. 

It will take a few minutes for this 'environment' to be created. 

Once you have the notebooks open using one of the following methods, you should follow the instructions in the notebook itself.

### 1. Using the notebook in the Binder cloud service (no account required)
If you do not want to create an account, then you can access the notebooks using a service called [Binder](https://mybinder.org). Please note that, using this option, once you exit from Binder any work will not be saved. If you wish to save your work you will need to save and download the notebook to your own computer before you exit Binder.

To access the notebooks use the following links, remember it may take a few minutes to start:

- [Data Visualisation](https://mybinder.org/v2/gh/UCLComputerScience/uclcs-ugy1-summerwelcome/master?filepath=data_visualisation.ipynb)
- [Algorithms 101](https://mybinder.org/v2/gh/UCLComputerScience/uclcs-ugy1-summerwelcome/master?filepath=algorithms101.ipynb)


### 2. Using the notebook in the Microsoft Azure Notebook cloud service (free account required)
If you want to save your work and return to it later, start by creating a free account on [Azure Notebooks](https://notebooks.azure.com). Please note that the Azure Notebooks service is being withdrawn on 9th October so if you want to access your work beyond that date you will need to download the files.

Then access the notebooks hosted on the Microsoft Azure cloud service at: [https://notebooks.azure.com/snicholson/projects/uclcs-ugy1-summerwelcome](https://notebooks.azure.com/snicholson/projects/uclcs-ugy1-summerwelcome)

You should first 'clone' the files. 
To do this, after clicking the above link, you should see a button in the top right corner of the screen with the word 'clone'. 
Press this to create a copy (if you are not already logged in to Microsoft Azure Notebooks and you didn't already create an account you will be prompted to create an account now). 
You may need to wait a few minutes during which a copy of the notebook is made and the 'environment' is created for you.

You can then access each of the notebooks by clicking on the relevant file name from within Azure:

- Data Visualisation: data_visualisation.ipynb
- Algorithms 101: algorithms101.ipynb	

### 3. Using a locally installed Python Jupyter notebook environment
If you already have a locally installed Python development environment and code editor, then you may be able to work out how to use the Jupyter notebook on your own machine. 
You will need to investigate options for doing this yourself depending on your own setup. 
You will need to install pysort in your local environment which you should be able to do with pip, e.g.: 
```python
pip install pysort
pip install pandas
pip install plotly
```

## Getting help
Ask for help by posting a message in the [Discussion forum on UCL Extend](https://extend.ucl.ac.uk/mod/forum/view.php?id=44916).

## Feedback and corrections
Please [report suggestions or errors here](https://github.com/UCLComputerScience/uclcs-ugy1-summerwelcome/issues). This repository is maintained by [Licia Capra](mailto:l.capra@ucl.ac.uk) and [Sarah Sanders](mailto:sarah.sanders@ucl.ac.uk).

## Data protection and privacy
You should not save any personal data in a notebook. Personal data is any data that could be used to identify you.

[Information on privacy for the Binder service can be found here](https://mybinder.readthedocs.io/en/latest/faq.html).

[Information on privacy for the Microsoft Azure Notebooks service can be found here](https://privacy.microsoft.com/en-gb/privacystatement).

## Acknowledgements (data visualisation notebook)
The introductory video in the data visualisation notebook is a TED talk given by Hans Rosling called ['The best stats you have ever seen'](https://www.ted.com/talks/hans_rosling_the_best_stats_you_ve_ever_seen?utm_campaign=tedspread&utm_medium=referral&utm_source=tedcomshare).

The code examples in the notebook make use of the [Plotly Express](https://plotly.com/python/plotly-express/) library. This library provides direct access to the Gapminder data set. There are also examples for the use of the Gapminder data in their help and documentation.

The Gapminder data can also be accessed freely at [Gapminder.org](https://www.gapminder.org/data/). The 'math_achievement_8th_grade.csv' file in this repository was downloaded from Gapminder.
