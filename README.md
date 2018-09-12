# Global_History
## For Udacity Project 1

### Introduction and Motivation for the Project
`"90 of the data ever created was created in the last two years."`
This Petter Bae Brandtzæg quote, as frightening as it is, betrays an even more frightening observation: We have ten times less data recorded in the past 2.8 million years of human history than we do about the years 2016-2018. and given this estimated exponential growth rate of data since the dawn of the computer age, we have 10^15 less data recorded from the dawn of history to the fall of the Berlin Wall than we do for the past 30 years. If we look to before the invention of modern statistics in the mid-1600's, the ammount of data we can analyze is miniscule. If we look to before the Domesday book in 1086, it gets downright depressing.

Luckily, nothing is restricting modern historians and academics from creating new data about the past. From digitized photos and text, documentation about archaeological digs, and even crowdsourced aggregations of academic consensus about historical periods, historians (and hobbyists like me) can create and explore datasets, using cutting-edge analytic tools to draw new understandings about the past, and helping answer questions like:
* What sociopolitical norms did different societies from across the Mediterranean and Asia develop over time in comparison with each other?
* Which of these norms were most and least likely to be observed in the same place and time?
* What are some of the distinct trajectories of related norms along which some groupings of societies but not others evolved?

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
