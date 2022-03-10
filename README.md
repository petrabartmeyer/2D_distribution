# 2D_distribution

The proposed analysis-flow (clustering_github.r) was coded in R(v3.6.3) using the Rstudio (v2021.09.0+351) interface. It uses  the libraries “spatstat”(v2.2-0), “dbscan”(v1.1-8), and “manipulate” (v1.0.1). The package "dbscan" generate the fibers cluster considering the OPTICS algorithm. The package "manipulate" allows to visualize the difference in clusters when changing the cluster threshold. For that, a Rstudio interface is necessary. A sliding bar will appear on the "Plot" tab, when you click on the gear symbol.


File "data.txt" presents three columns, where the first two columns are the X and Y position of the fibers' centroid, and the third column is the diameter of the fibers. The graphs and .csv files delivered by the script will be save on folder "Results". 

To use the script one has to set the maximum diameter of small fibers on line 9, the maximum diameter of medium fibers on line 10. The number of neighbor the analysis should consider is set on line 11.  The path for the raw data file should be set on line 12, a tip is put the path from the the C: or Home to the location of the files, it will help to see all the files on the folder. There is no need to include the name of the file, only the location, it allows to run multiples files from the same folder. The name of the file (or files) that should be analyzed are defined in line 15. The name of the folder where the results will be saved is define on line 19. 
