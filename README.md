# VALKyRie_dataset
This is supplementary material to a conference article. For details see "Effects of visualisation quality on the sense of presence in a pedestrian simulator" for the ICHVR2022 (abstract submitted)

# Acknowledgements
The reported work was conducted based on funding provided by the Helmholtz community.

# Authors
Michaela Rehm, Fabian Utesch, Kilian Gröne, Eric Nicolay, Johannes Rehm, Rens-Ronal Rosenthal, Gerald Temme, Amit Yadava, Min Zhao, Martin Fischer

Contact: michaela.rehm@dlr.de

# Data collection
The study was performed at the German Aerospace Center (DLR) in Braunschweig Germany in November 2021.

# Sample
Data of 30 who walked as pedestrians in a virtual copy of the Tostmannplatz intersection in Braunschweig Germany (GPS 52.296181, 10.540733). 

# Setup
Subject used a HTC Vive Pro Eye as VR headset, two Vive Controllers for interaction with the environment and walked on an Omfinity Omnideck 306° treadmill.

# Procedure
In two trainings subjects learned to interact with objects and to walk on the treadmill. The training took about 10 minutes for each of the two training maps.
Subjects then completed the test course three times with different settings in visual quality (low, medium, high) in random order balanced over participants with the latin-square method. Each map was completed in about 15 minutes.

# Data set
Subject IDs were substituted with random numbers to for anonymization.

# Analysis
Data were processed in R (R Core Team, 2021) version 4.1.2 and R Studio (RStudio Team, 2021)
version 2021.09.2. A bayesian statistical analysis was performed with JASP (JASP Team, 2021)
version 0.16. For details about the interpretation of Bayes Factors see Nuzzo (2017) Table 3.
Error bars in all figures indicate 95% confidence intervals.

##NOTE
When ANOVA is run in JASP the results in the .jasp file are likely to slightly differ from the reported numbers in the paper. This is due to the fact that analysis are based on algorithms like Markov chain Monte Carlo (MCMC). The degree of variation is expressed in the error percentage. The higher the error the higher the variation (see Goss-Sampson, 2020).

# References

Goss-Sampson, M. A. (2020, May). Bayesian Inference in JASP: A Guide for Students. https://doi.org/10.17605/OSF.IO/CKNXM

JASP Team. (2021). Jasp. Retrieved from https://jasp-stats.org/

Nuzzo, R. L. (2017). An Introduction to Bayesian Data Analysis for Correlations. An
Introduction to Bayesian Data Analysis for Correlations, 9 (12), 1278–1282. doi: 10.1016/
j.pmrj.2017.11.003

R Core Team. (2021). R: A language and environment for statistical computing [Computer
software manual]. Vienna, Austria. Retrieved from https://www.R-project.org

RStudio Team. (2021). Rstudio: Integrated development environment for r [Computer software
manual]. Boston, MA. Retrieved from http://www.rstudio.com/