# Clustering Genes according to their Plant and Small-Molecule Drug Associations through the use of Self-Organizing Maps
This is a project done for a class entitled "Representations and Algorithms for Computational Biochemistry" in UPM. The motivation of this project came from the thesis of a UP alumni where different groups were tasked to replicate portions of the project from scratch. With the guidance of the thesis paper, our group was tasked to cluster genes according to their plant and small-molecule drug (SMD) associations with the implementation of self-organizing maps (SOM), an unsupervised learning method.

This was programmed with Google Colab notebooks and was then uploaded into this Git repository, together with our final paper. Data was extracted from DrugBank and Dr. Dukes Phytochemical and Ethnobotanical Databases with the help of the BeautifulSoup package of Python. Gene-SMD and Gene-Plant Tables were then constructed and then transformed into graphs, with the help of the NetworkX, suitable for the application of SOM that needed the sklearn and minisom packages.

[Reference Paper]
PlaPhy-SMD: A Database System of Plants and their Phytochemicals Integrated with Small-Molecule Drugs and their Condition and Gene Associations with Clustering and Product Ingredient Matching
https://ieeexplore.ieee.org/document/9284382

