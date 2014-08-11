# Slides for the Open Scholarship Tools a Whirlwind Tour talk at Wikimania 2014

## About 

This repo contains the iPython notebook that was used to generate slides for a talk at the [Open Scholarship 3](https://wikimania2014.wikimedia.org/wiki/Submissions/Open_Scholarship_Tools_-_a_whirlwind_tour.) session at Wikimania2014 in London.


## Viewing the slideshow 

The slides were created in iPython and converted into html using reveal.js. As of 2014-08-11, you can see an instance of the slides [here](http://www.mulvany.net/presentations/WikimaniaOpenScholarshipTalk.slides.html#/).

## Viewing the iPython notebook

The notebook can be viewed using [http://nbviewer.ipython.org/]() [here](http://nbviewer.ipython.org/github/IanMulvany/wikimania-open-scholarship-tools/blob/master/WikimaniaOpenScholarshipTalk.ipynb). 

## Running the presentation locally

You can get up and running with this presentaiton yourself. You need to follow the folloing steps, once you have [pip](http://pip.readthedocs.org/en/latest/installing.html) installed.

### Install IPython
>
$  pip install ipython[all]

### Get this notebook
>
$ git clone this repo  
$ cd into this repo

### Generating slides from the ipython notebook, and serving
To generate html slides from the ipyton notebook, with ipython installed run
>
$ ipython nbconvert WikimaniaOpenScholarshipTalk.ipynb  --to slides --post serve

### tutorial on using iPython to build slides
Have a look at [this presentation](http://damianavila.github.io/scipy2013_talks/index.html#/27/2) for an overview of what you can do.
