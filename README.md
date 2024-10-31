# scRNAtrap
The ***scRNAtrap*** is a project for identifying gene fragments in **single-cell sequencing**. The project provides a comprehensive set of tools designed to analyze **potential viruses within single-cell sequencing data** efficiently and easily.

## System requirements
**The scRNAtrap is developed using both Python and R.**
The following are the version numbers of the software or algorithms used in this study.

	Python 3.9.19

	NumPy 1.26.4
	PyTorch 2.3.1
	Scikit-learn 1.2.2
	SciPy 1.13.1
	matplotlib 3.8.4
	biopython 1.78
	zipp 3.17.0
	pandas 1.2.3

	R 4.1.0
	dplyr_1.1.2 
	Seurat_4.3.0.1
	patchwork_1.1.2
	tidyverse_2.0.0
	magrittr_2.0.3
	ggsci_3.0.0
	pheatmap_1.0.12
	ggplot2_3.4.4

## Installation
**Python packages can be installed in a shell environment using the "conda install" command.**
**E.g.**
    conda install Python package name1
    conda install Python package name2=1.2.3

**R packages can be installed in the R environment using the "install.packege()" or "BiocManager::install()" commands.**
**E.g.**
    install.packege("packege_name")
  	if(!"BiocManager"%in%installed.packages()){ 
  	install.packages("BiocManager")}
   	if(!"packege_name"%in%installed.packages()){ 
	  BiocManager::install("packege_name")}
	  if (!"devtools" %in% installed.packages()) {
  	install.packages("devtools")}
   	devtools::install_github("packege_name")

## Code Overview and Instructions
**The numbers described here correspond to the numbers in the folders within the compressed file(code_set.zip).**
1.cut











## Contact
If you have any questions or feedback, please create an issue on Github or email us at either ***tanghaijun@sr.gxmu.edu.cn*** or ***docharuko@gmail.com***.
