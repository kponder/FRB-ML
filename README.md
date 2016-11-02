# FRB-ML
Looking for patterns in Fast Radio Bursts (FRBs) using Unsupervised Machine Learning. 

FRBs are microsecond pulses in the radio wavelengths that have unknown sources. In 2014, there were 7 FRBs published. 
When the width of the pulse was plotted versus dispersion measure, there appeared to be 2 distinct populations.
Sumit Sarbadhicary, Jeff Newman, and I explored how robust these "by eye" populations were with the help of Duncan Lorimer and Akshaya Rane. 
With 7 data points and examining 3 different unsupervised learning algorithms, it was not a statistically significant result, so I determined how many FRBs would be needed in order to get a significant result. 

I determined that the ~70 FRBs would be need to have a robust result. The exact number varied based on machine learningn algorithm. However, then more FRBs were observed and added to the sample, the 2 populations of FRBs disappeared "by eye" and statistically. 

The three unsupervised learning algorithms explored here are
1. K-means
2. Hieararchical 
3. DBSCAN

All codes are in python notebooks. I used scikit-learn to implement the algorithms.
