# Global_History
## For Udacity Project 1

### Introduction and Motivation for the Project
Data created in historical periods is extremely limited, but data scientists can create new data *about* the past in order to draw new insights though data analysis and machine learning. In this project, I use a dataset compiled by a group of historical experts about societal normas across time in different areas to answer three questions, outlined below under *Summary of Analysis Results.* Final analysis can be found in the associated [blog post](https://medium.com/@briantfriederich/empires-and-eda-4cbefc91a96a).

### Libraries
* Numpy
* Pandas
* MatPlotLib
* Seaborn
* SciKit-Learn

### Description of each file in repository
* *README.md* README file informing users of the project summary, dependencies, files in the repository, a summary of results, and acknowledgements.
* *empires_and_eda.ipynb* Jupyter notebook with the code for my analysis.
* *data/axial_age.csv* CSV dataset of the presence or absence 12 sociopolitical atributes over 10 geographic areas for each 100 years, ranging from the years 5300 BCE to 1800 CE.

*This research employed data from the Seshat Databank (seshatdatabank.info) under Creative Commons Attribution Non-Commercial (CC By-NC SA) licensing.*
[Turchin P. et al. 2015. “Seshat: The Global History Databank.” Cliodynamics 6(1): 77–107](https://doi.org/10.21237/C7clio6127917)
[Mullins, D., Hoyer, D. et al. 2018. “A Systematic Assessment of ‘Axial Age’ Proposals Using Global Comparative Historical Evidence.” American Sociological Review 83(3): 596–626](https://doi.org/10.1177/0003122418772567)

### Summary of Analysis Results
In this notebook I answer the three following questions throught the corresponding methods outlined below:
* What sociopolitical norms did different societies from across the Mediterranean and Asia develop over time in comparison with each other? *Comparative barplots*
* Which of these norms were most and least likely to be observed in the same place and time? *Correlation matrix*
* What are some of the distinct trajectories of related norms along which some groupings of societies but not others evolved? *Principal Component Analysis*


### Acknowledgements
Special thanks to [Seshat](http://seshatdatabank.info) for making several datasets from their global history databsnk publically available, and specila thanks to [Udacity](https://www.udacity.com), whose rubric inspired this project and without whom my PCA would have taken much longer.
