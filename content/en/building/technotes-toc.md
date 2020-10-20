+++
author = "Shawn Graham"
title = "Your Guide to the Technical Notes"
date = "2020-10-10"
#description = "Lorem Ipsum Dolor Si Amet"

image = "images/landscape.jpg"
+++

## Basic Skills

We are going to use Jupyter Notebooks in this class. For a global overview of how Jupyter notebooks work and are used in humanities research, see Quinn Dombrowski's lesson in [_The Programming Historian_](https://programminghistorian.org/en/lessons/jupyter-notebooks). The links below go to either live notebooks that you can work through, or guide you through some of the same steps that Dombrowski discusses, but with more detail.

+ Working with the Command Line (PC) or Terminal (Mac)
  - A walkthrough, by Chantal Brousseau

+ [Introduction to Jupyter Notebooks](https://mybinder.org/v2/gh/shawngraham/dhmuse-notebooks/master?urlpath=notebooks/getting-started-with-jupyter.ipynb)
    - Courtesy Nathan Kelber and Ted Lawless for JSTOR Labs, CC-BY
    - This notebook introduces Jupyter notebooks and Python for absolute beginners.
    - Going further: Kelber and Lawless have a number of notebooks for working with JSTOR's 'Data for Research' dataset creation service; [find out more here](https://tdm-pilot.org/)

+ [Running Jupyter Notebooks on Your Own Machine](#)
  - A walkthrough, by Chantal Brousseau

+ [Using Git on the Command Line to Keep your Notebook Under Version Control](#)
  - A walkthrough, by Dr. Graham

+ [How to launch your Notebook in a computational binder online with mybinder.org](#)
  - A walkthrough, by Dr. Graham

+ [Introduction to Python](https://mybinder.org/v2/gh/shawngraham/dhmuse-notebooks/master?urlpath=python-basics-1.ipynb)

## Retrieve and Visualize Data

+ Loading simple Data into a Notebook that you've found online

+ [Working with Pandas to Manipulate Data](https://mybinder.org/v2/gh/shawngraham/dhmuse-notebooks/master?urlpath=pandas-1.ipynb)

+ Visualizing Data with Bokeh & Python
    - This notebook is the one that accompanies the tutorial by Charlie Harper in [_The Programming Historian_](https://programminghistorian.org/en/lessons/visualizing-with-bokeh)
    - You can launch the notebook [here](https://mybinder.org/v2/gh/shawngraham/dhmuse-notebooks/master?urlpath=viz-w-bokeh.ipynb); this will let you skip setting up the virtual environment (a way of keeping all of your lego pieces for each task separate so they don't cause conflicts).

+ Using OpenRefine to Obtain Data
  - This tutorial adapts the Programming Historian lesson by Evan Peter Williamson ["Fetching and Parsing Data from the Web with OpenRefine", especially its example 2](https://programminghistorian.org/en/lessons/fetch-and-parse-data-with-openrefine#example-2-url-queries-and-parsing-json).
  - Tutorial link [here](#).

+ Extract Illustrated Pages from the Hathi Trust & Internet Archive
  - This tutorial & associated notebooks are developed from Stephen Krewson's piece for the Programming Historian, ["Extracting Illustrated Pages from Digital Libraries with Python"](https://programminghistorian.org/en/lessons/extracting-illustrated-pages)
  - You'll search for images related to "Ottawa".
  - Tutorial link [here](#). [Hathi Notebook](https://mybinder.org/v2/gh/shawngraham/dhmuse-notebooks/master?urlpath=hathitrust.ipynb); [Internet Archive Notebook](https://mybinder.org/v2/gh/shawngraham/dhmuse-notebooks/master?urlpath=internetarchive.ipynb)
  - memo to self: the json file for the notebooks is in the 'data' folder

+ Retrieve data from a 'datasette'-created API [launch binder here](http://mybinder.org/v2/gh/o-date/open-context-jupyter/master?urlpath=retrieving data from a datasette api.ipynb)
  - note that the 'api_search_url' variable might need to be changed to point to the survey markers datasette or the CARF excavation datasette re Fort Frontenac (see below for url)

## Documentation

+ Building an API with Datasette

+ Building a documentation website with Mkdocs
  - MKDocs is a python module that will turn a folder with markdown documents into a functioning website

## Creativity

For when you're ready to push things further.

+ [Sonification](https://mybinder.org/v2/gh/o-date/sonification/master?urlpath=Intro to Sonification.ipynb)
  - An overview of how and why you might sonify data

+ [Image Glitching](https://mybinder.org/v2/gh/o-date/creativity/master?urlpath=Glitching an image with prism sorting.ipynb)
  - An overview of why glitching an image might be one way of letting people play with collections

+ [An introduction to 'Processing', a language for quick sketches, visualizations, and artwork](https://mybinder.org/v2/gh/o-date/processing/master?urlpath=python with processing.ipynb)
  - A simple introduction to a language that enables creative expression (Brian Foo, the 'Data Driven DJ' uses processing to make visualizations to accompany his sonifications. See for instance his work, [Lee and Jackson](https://datadrivendj.com/tracks/painters/).)

## Ottawa Datasets

+ There are certain datasets already available for the Ottawa GLAM scene; some were created by students in the previous edition of this course.

   + Survey markers from the CSTM (compiled by Sherwin et al) https://cstm-demo2.herokuapp.com/cstm-markers/

   +This API makes available some 400 record cards from the CARF excavations of Fort Frontenac in Kingston. http://fort-frontenac-excavation.herokuapp.com/.