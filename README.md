[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
Introduction to single cell RNA-Seq analysis
============================================
overview: Tutorial and code to reproduce JHU Neurocog II scRNA-Seq lab 2022
class: Neurocog II Lecture + Lab
date: February 24, 2022

# Overview
In this repository you will find the code and accessory materials for the Neurocog II scRNA-Seq lab.  

# Learning Objectives
• Understand the basic steps of single cell RNA-Sequencing analysis workflows
• Develop a baseline awareness of cellular heterogeneity both between and within cell 'types'.
• Learn to identify and examine cell state transitions via pseudotime analysis
• Understanding the application of dimensionality reduction to high-dimensional data visualization and analysis.

# Before Class
Before class on Thursday, please attempt to setup your computer environment to meet these minimal requirements:
1) Install RStudio Desktop and R (https://www.rstudio.com/products/rstudio/)
  - Please validate that you can open RStudio and that you have a (relatively recent; v4.0 or later) version of R working.
2) If you haven't already, please clone this repository into a directory where you will be working to complete the lab.
  - `git clone git@github.com:gofflab/neurocog_scRNA-Seq_2022.git`
  - Or alternatively, you can unpack the compressed (zipped) project that was distributed to you.
3) You can open the RStudio project file in the root directory of the project `neurocog_scRNA-Seq_2022.Rproj` in RStudio.
4) The main document that we will be working through to complete is in `scripts/Neurocog_11_scRNA-Seq_Lab_2022.Rmd`. The objective by the end of lab on thursday will be to be able to execute and 'knit' this entire document as a complete example of an scRNA-Seq dataset.
5) Please attempt to install the following packages as needed (you can find this list and example installation instructions in the code block named `install_packages` on line 52 of the main script):
  `"Matrix","monocle3","RcppML","biomaRt","tidyverse","celldex","SingleR"`

If you have any issues with the installation and setup of this script, please feel free to email me.
