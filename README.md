# MDS-for-NorthEuraLex
In the jupyter notebook I compute the pairwise distances between the languages in the NorthEuraLex database, 
apply multidimensional scaling and visualize the resulting 3 dimensions, and visualize them. 
Then spatial interpolation is done via ordinary kriging first and then with generalized additive models.

To run the jupyter notebook only the working directory in the first code cell needs to be changed, 
everything else should run - provided the necessary libraries are installed.

Needed R Libraries:
- gstat
- sf
- spData
- terra
- tidyverse
- tmap
