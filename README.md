# 2D_distribution

The proposed analysis-flow (clustering_github.r) was coded in R(v3.6.3) using the Rstudio (v2021.09.0+351) interface. It uses  the libraries “spatstat”(v2.2-0), “dbscan”(v1.1-8), and “manipulate” (v1.0.1). The package "dbscan" generate the fibers cluster considering the OPTICS algorithm. The package "manipulate" allows to visualize the difference in clusters when changing the cluster threshold. For that, a Rstudio interface is necessary. A sliding bar will appear on the "Plot" tab, when you click on the gear symbol.


File "data.txt" presents three columns, where the first two columns are the X and Y position of the fibers' centroid, and the third column is the diameter of the fibers. The graphs and .csv files delivered by the script will be save on folder "Results". 
