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
For this analysis, I'm using the relatively small Axial Age dataset by Seshat, "a large, international, multidisciplinary team of evolutionary scientists, historians, anthropologists, archaeologists, economists, and other social scientists." The publically available dataset tracks a variety of sociopolitical norms and their development across key areas in Afro-Eurasia to assess, and in their findings cast doubt upon, the theory that these cultural conditions let to the religious and philosophical renaissance known as the "axial age." The specific scores for each sociopolitical norm for each date (varying time spans between 5300 BCE and 1800 CE in 100 year increments) within 10 NGAs (natural geographic area) were agreed-upon by a group of experts and compiled into the dataset.

*This research employed data from the Seshat Databank (seshatdatabank.info) under Creative Commons Attribution Non-Commercial (CC By-NC SA) licensing.*
[Turchin P. et al. 2015. “Seshat: The Global History Databank.” Cliodynamics 6(1): 77–107](https://doi.org/10.21237/C7clio6127917)
[Mullins, D., Hoyer, D. et al. 2018. “A Systematic Assessment of ‘Axial Age’ Proposals Using Global Comparative Historical Evidence.” American Sociological Review 83(3): 596–626](https://doi.org/10.1177/0003122418772567)

### Summary of Analysis Results

**What sociopolitical norms did different societies from across the Mediterranean and Asia develop over time in comparison with each other?**
With the exception of Cambodia and the Kachi Plain repectively, moralistic punishment and the belief in omniscient supernatural beings was a strong feature throught the Classical world but not in Southern and Eastern Asian societies. Moralizing norms, promotion of prosociality, the belief that rulers were not gods, a formal legal code, general applicability of law, constraints on the executive, and full time bureaucrats were features common to all NGAs except Kansai. Galilee, the Kachi Plain, the Konya Plain, Susiana, Upper Egypt, and to a lesser extent Crete scored markedly higher on equating rulers and commoners with elites. Constraints on the executive and impeachment appear to be noticeably Roman traits. This is flipped in terms of full-time bureaucrats.

**Which of these norms were most and least likely to be observed in the same place and time?**
A formal legal code, promotion of prosociality, and a general applicability of law were most likely to be observed together, with a strong positive relationship in the data. Impeachment was the least likely feature to co-occur with equating elites and commoners and equating rulers and commoners, each with a mild negative relationship. Impeachment also correlated negatively, though much more weakly, with the presence of full-time bureaucrats.

**What are some of the distinct trajectories of related norms along which some groupings of societies but not others evolved?**
Dimension 2, explaining 14% of total variance, was characterized by mild lack of belief in omniscient being and a strong belief that rulers are not gods and can be institutionally constrained. Social stratification is high and bureaucracy is weak, though there is a strong legal framework. This dimension would probably sound familair to many classicists as Classical Ancient Greek Political philosophy. Dimension 3, explaining 10% of variance is characterized by strong moralizing norms and prosociality. Belief in both an omniscient god and divine rulers is low, though rulers are much more respected than commoners, relatively unconstrained, and unimpeachable. There is a very strong bureaucracy and a highly sophisticated legal framework. This dimension also sounds very familair to asianists as Confucian political philosophy. These two philosophies' designation as separate dimensions shows that they're not mutually exclusive, with different societies poentially displaying mixes of one, both or neither dimensions' characteristics.

### Acknowledgements
Special thanks to [Seshat](http://seshatdatabank.info) for making several datasets from their global history databsnk publically available, and specila thanks to [Udacity](https://www.udacity.com), whose rubric inspired this project and without whom my PCA would have taken much longer.
