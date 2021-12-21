# HUDK4050EDM--Portfolio of Siyuan Gu

You can see the individual coding exercise records(ICEs) and analysis challenge assignments(ACAs) under the Notebooks-of-ICEs-ACAs branch of this repo. Here is the link: https://github.com/AGFlywire3/HUDK4050EDM--Portfolio/tree/AGFlywire3-Notebooks-of-ICEs-ACAs
* All works finished under Professor Zhichun(Lukas) Liu's tutorial from Teachers College, Columbia University.
* The reflective essay briefly describe the ovarall experience of the HUDK-4050 Core Mthds Educ Data Mining course, and some introduction before and after taking this course.
* The Creative EDM Assignment is accomplished by co-writers from the same class, they are Deji Huaqu, Huancheng Xu, Guotai Sun, Yuetong Lyu and me.
  
  Moreover, after I finished all the exercises and challenges, I did a double check by rerunning it through Jupyter Notebook. I found that there might be a version conflict caused by `sklearn` packages from python. When I tried to apply for of `silhouette_visualizer` from `yellowbrick.cluster` to get SilhouetteScore of clustering, I have to downgrade the version of sklearn to 0.23.2 rather than 0.24 as the higher version produced a bug and stopped silhouette_visualizer working correctly. While the lower version did not work well to realize the analysis of ICE5 (see line 15, again correlated with `silhouette_visualizer` from `yellowbrick.cluster`). Since 0.24 version of `sklearn` caused a more serious problem than 0.23.2, I chose to ignore the problem shown in ICE5.
