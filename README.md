# Computational Geosciences

This repository contains all material for my lectures within the Part III Computational Geosciences option. 

Lecture notes and all codes are combined into Jupyter notebooks. For each lecture a complete version of the notebook is provided with solutions to the practical exercises. 

## Installation 

The python codes require a number of libraries. Installation is recomended using the **poetry dependency manager**:

https://python-poetry.org/

First you will need to install poetry on your computer. This is easily done following the instructions at:

https://python-poetry.org/docs/#installing-with-the-official-installer

Note that it may be necessary to add poerty to the path on your computer. Some information on this 
is included within the linked instructions, but you may need to look up specific for your operating system.

Once this is done, you need to clone the git repository. For informatoin on how to do this see:
 
 https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository


Change directory into the repository and then type:
```
poetry install
```
This creates a new virtual environment which has all necessary packages installed. 

You can then launch the notebook for the first lecture by typing:
```
poetry run jupyter notebook gravity_lecture/gravity.ipynb 
```
and similarly for the other notebooks. 

## Running the codes using binder

As an alternative to running the codes locally, you can use the free online service https://mybinder.org/

To do this, open the website and then copy:

```https://github.com/da380/ComputationalGeosciences``` 

as the URL for the GitHub repository. 
You can then press the launch button and after a minute or so the notebooks will be usuable through your web-browswer. 
