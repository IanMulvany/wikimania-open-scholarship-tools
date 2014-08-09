# Slides for the Open Scholarship Tools a Whirlwind Tour talk at Wikimania 2014

The idea is to use some of the tools that we are actually going to talk about to create the presentation.

pip: http://pip.readthedocs.org/en/latest/installing.html

## Install IPython
>
$  pip install ipython[all]

## Get this notebook
>
$ git clone this repo  
$ cd into this repo

## Generating slides from the ipython notebook, and serving
To generate html slides from the ipyton notebook, with ipython installed run
>
$ ipython nbconvert WikimaniaOpenScholarshipTalk.ipynb  --to slides --post serve

## tutorial on using iPython to build slides
Have a look at [this presentation](http://damianavila.github.io/scipy2013_talks/index.html#/27/2) for an overview of what you can do.
