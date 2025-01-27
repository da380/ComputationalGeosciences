# Computational Geosciences

This repository contains all material for my lectures within the Part III Computational Geosciences option. 

Lecture notes and all codes are combined into Jupyter notebooks. For each lecture a complete version of the notebook is provided with solutions to the practical exercises. 

## Installation 

The python codes require a number of libraries. Installation is recomended using the **poetry dependency manager**:

https://python-poetry.org/

First you will need to install poetry on your computer. This is easily done following the instructions at:

https://python-poetry.org/docs/#installing-with-the-official-installer

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