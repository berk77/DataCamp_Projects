# The GitHub History of the Scala Language

In this project, we'll be challenged to read in, clean up, and visualize the real-world project repository of Scala that spans data from a version control system (Git) as well as a project hosting site (GitHub). With almost 30,000 commits and a history spanning over ten years, Scala is a mature language. We will find out who has had the most influence on its development and who are the experts.

## Data

The dataset we will use, which has been previously mined and extracted from GitHub, is comprised of three files:

* <a href="datasets/pulls_2011-2013.csv">pulls_2011-2013.csv</a> contains the basic information about the pull requests, and spans from the end of 2011 up to (but not including) 2014.
* <a href="datasets/pulls_2014-2018.csv">pulls_2014-2018.csv</a> contains identical information, and spans from 2014 up to 2018.
* <a href="datasets/pull_files.csv">pull_files.csv</a> contains the files that were modified by each pull request.

## Preparing and cleaning the data

* First, the data from two separate pull DataFrames was combined.
* All times have been converted to UTC to facilitate comparisons.
* The extracted data comes in two separate files, pull and pull files. Two DataFrames have been combined to make it easier for us to analyze data in future tasks.

## Results
* For Scala, the activity graph of the project was drawn. Calculated the number of pull requests sent per (calendar) month over the life of the project. These numbers were then plotted to see the trend of the contributions.
* In order to evaluate the dynamics of the community, a histogram of the number of pull requests submitted by each user was plotted. A distribution showing only a small number of people contributing to a small number of pull requests can be used as an indication that the project is not meeting new contributors.

I wanted to give a brief information about the project and results in here. <a href="https://nbviewer.jupyter.org/github/berk77/DataCamp_Projects/blob/main/The%20GitHub%20History%20of%20the%20Scala%20Language/notebook.ipynb">If you want, you can examine the project in more detail here.</a>
