BootStrap: shub

From: nickjer/singularity-r:3.5.1



%help
This is singularity 3.0.2  image for  R 3.5.1


%setup


%post
 R --slave -e 'install.packages("BiocManager", repos="https://cloud.r-project.org/")'
 R --slave -e 'BiocManager::install("arrayQualityMetrics", version = "3.8")'
%labels
   AUTHOR  Amjad Syed

   Email  amjadcsu@gmail.com



