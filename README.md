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

## Generating slides from the ipython notebook
To generate html slides from the ipyton notebook, with ipython installed run
> 
$ ipython nbconvert your_slides.ipynb --to slides

## Load the presentation from a local server 
>
$ python -m SimpleHTTPServer

Then open the browser at the localhost and navigate to your presentation, or something. 

## tutorial on using iPython to build slides
Have a look at [this presentation](http://damianavila.github.io/scipy2013_talks/index.html#/27/2) for an overview of what you can do. 