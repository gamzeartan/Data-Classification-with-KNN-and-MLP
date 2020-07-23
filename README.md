# Data Classification with KNN and MLP
 Classification of Magic Gamma Telescope data set with KNN and Multilayer Perceptron methods and comparison of results.
 
 # You should open the .ipynb code via Jupyter Notebook.The data set is in .csv format. You should run it by changing the file path in the code.
 
 # Data Set Link:
 https://archive.ics.uci.edu/ml/datasets/magic+gamma+telescope
 
 Attribute Information:

1. fLength: continuous # major axis of ellipse [mm]
2. fWidth: continuous # minor axis of ellipse [mm]
3. fSize: continuous # 10-log of sum of content of all pixels [in #phot]
4. fConc: continuous # ratio of sum of two highest pixels over fSize [ratio]
5. fConc1: continuous # ratio of highest pixel over fSize [ratio]
6. fAsym: continuous # distance from highest pixel to center, projected onto major axis [mm]
7. fM3Long: continuous # 3rd root of third moment along major axis [mm]
8. fM3Trans: continuous # 3rd root of third moment along minor axis [mm]
9. fAlpha: continuous # angle of major axis with vector to origin [deg]
10. fDist: continuous # distance from origin to center of ellipse [mm]
11. class: g,h # gamma (signal), hadron (background)

g = gamma (signal): 12332
h = hadron (background): 6688
 
The Magic Gamma Telescope system, consisting of two Cherenkov telescopes positioned approximately 2000 meters above sea level, is designed to detect gamma rays. They observe the upper atmosphere layers. The determination of gamma rays from hadron signals is one of the important issues for Astronomy. The dataset was taken from the online machine learning site called UCl. The dataset has two classes, gamma and hadron. The goal is to classify gamma rays from hadron signals. For this purpose, machine learning techniques k-nearest neigbour and multilayer percepton were used. Analysis of the data set and the accuracy result of the classifier were compared.


# The results of the classifier performances:
# K-NN: 0.84
# MLP: 0.88
