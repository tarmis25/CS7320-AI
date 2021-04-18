<!-- #region -->
# CS 5/7320 Artificial Intelligence

<img src="http://aima.cs.berkeley.edu/cover2.jpg" align="right" width="25%">


Assignments and examples for the course in CS 5/7320 Artificial Intelligence taught at the 
[Computer Science Department at SMU](https://www.smu.edu/Lyle/Academics/Departments/CS) by [Michael Hahsler](https://michael.hahsler.net/). Slides and more information for students taking the course can be found on 
[SMU's Canvas](https://www.smu.edu/OIT/Services/Canvas).


The code examples follow the textbook [Artificial Intelligence: A Modern Approach](http://aima.cs.berkeley.edu/) by Russell and Norvig. The code in this repository is intended to be simple to focus more on the basic AI concepts and less on the use of advanced implementation techniques (e.g., object-oriented design).
More complex code examples accompanying the textbook can be found at the [GitHub repository aimacode](https://github.com/aimacode).  

## Covered Chapters

* Chapter 2: [Intelligent Agents](Agents) 
* Chapter 3: [Solving Problems by Search](Search)
* Chapter 4: Search in Complex Environments: [Local Search,](Local_Search) [Nondeterministic Actions](Games)
* Chapter 5: [Adversarial Search and Games](Games)
* Chapter 6: [Constraint Satisfaction Problem](CSP)
* Chapters 12-13: [Uncertainty and Probabilistic Reasoning](Uncertainty)
* Chapter 19: [Learning from Examples (Machine Learning)](ML)

## Installing Python and Jupyter Notebook

You can experiment with the code online without installation using Binder. 
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mhahsler/CS7320-AI/HEAD)

To work on assignments, you need to install Python and Jupyter Notebook on your system, you can 
* __[prefered solution]__ install [Docker](https://docs.docker.com/get-docker/) and 
execute `docker run -p 8888:8888 jupyter/datascience-notebook` to download and create a running container of
the [jupyter/datascience-notebook](https://hub.docker.com/r/jupyter/datascience-notebook) image. 
From now on, use `docker ps -a` to list containers and their container id, `docker stop <container id>` and `docker start <container id>` to stop and start the container
(do not use `run` again because it will create a new container), or 
* install Python, Jupyter Notebook and the needed packages (e.g., via [Anaconda](https://www.anaconda.com/)).


## Learning Python and Jupyer Notebook

If you are not familiar with Python then you should work through a tutorial like [this](https://www.w3schools.com/python/default.asp) to learn the basics about Python and the packages `numpy` and `pandas`. Another good source to learn Python are 
the notebooks [intro to Python](https://github.com/eclarson/MachineLearningNotebooks/blob/master/0.%20Python_Intro%20(optional).ipynb)
and [intro to numpy and pandas](https://github.com/eclarson/MachineLearningNotebooks/blob/master/01_Numpy%20and%20Pandas%20Intro.ipynb)
by Eric Larson. Some code examples that help with the assignments are available [here](Python_Code_Examples).

How to use Jupyter Notebook is covered in many online tutorials like the [Jupyer Notebook tutorial](https://www.dataquest.io/blog/jupyter-notebook-tutorial/).

## Working on Assignments

You can fork this repository to work on your solutions locally. 
Submit a pdf of the compiled notebook (either export the notebook as pdf or print to pdf). The notebook needs to be a complete project report with documentation (including your design choices), code and results (e.g., tables with simulation results) with a short discussion of what they mean. Use the provided notebook cells and insert additional code and markdown cells as needed.

## License
All code and documents in this repository are provided under [Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0) License](https://creativecommons.org/licenses/by-sa/4.0/)

![CC BY-SA 4.0](https://licensebuttons.net/l/by-sa/3.0/88x31.png)
<!-- #endregion -->
