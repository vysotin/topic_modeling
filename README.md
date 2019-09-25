# Topic Modeling and Sentiment per topic analysis

My goal was to create end-to-end solution for extracting topics from the large corpus of texts that also have a 
date attribute, like news, scientific articles, etc. 
I will also look at evolution of topics in given corpus and explore the ways to extract the topic related sentiment for given text.
The code is given in python notebook topic_modeling.ipynb. HTML image of this this notebook with calculated outputs is 
in topic_modeling.html

## Setup and running

To run this notbook use python environment based on python 3.7. The environment can be set up using requirements.txt for pip installation 
(pip install -r requirements.txt) or environment.yml for creating conda environment (conda env create -f environment.yml).

To start notebook in given environment run the command: 
```
jupiter notebook topic_modeling.ipynb
```