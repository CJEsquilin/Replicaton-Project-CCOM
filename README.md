# PR2017replicaton, replication

## Members: Michael Terrefortes, Jasiel Rivera, Jose Portela, Christian Esquilin

Video: https://drive.google.com/file/d/10GUT0goaHgYjGryrgEPDRMKvsyvJwclG/view?usp=sharing \n
Github de projecto: https://github.com/CJEsquilin/Replicaton-Project-CCOM \n
Google Colab: https://colab.research.google.com/drive/1otpWQ2f_TmAUp18fOPggoQFKCxLGwoVc?usp=sharing \n
Github original: https://github.com/areyesq89/PR2017replicaton \n

## Instrucciones: Para correr el replicaton en Google Colab presione el enlace provisto. Debe subir los archivos “rawPharmacoData.csv” y “summarizedPharmacoData.csv” para poder correr el código en Colab. Por otro lado, es recomendable que presione “restart and run all” para correr el código. También se incluyen los enlaces del Github repository y video. Para ver el video debe bajar el video del enlace. 

Clone or download this repository to your computer and open the `.Rmd` files in Rstudio.

## Main Analysis Template R Markdown:

* [`analysis_template.Rmd`](https://github.com/areyesq89/PR2017replicaton/blob/master/analysis_template.Rmd) : R markdown template which each team will use to create a fully reproducible analysis with the goal of assessing and interpreting the replicability of two pharmacogenomic experiments. This document will contain all of the text and code of their analyses, which are quided by a series of questions. The tools and concepts needed to answer the questions are explored in the tutorials. **ANSWERED IN Replication.ipynb notebook.** 

## Datasets: Same as before in original github

* [`rawPharmacoData.csv`](https://github.com/areyesq89/PR2017replicaton/blob/master/rawPharmacoData.csv) : raw data file generated by `downloadData.R` that contains drug response data at every dose and for each cell line and drug used in both studies. 

* [`summarizedPharmacoData.csv`](https://github.com/areyesq89/PR2017replicaton/blob/master/summarizedPharmacoData.csv) : summarized data file generated by `downloadData.R` that contains drug response data (combined over all doses) for each cell line and drug used in both studies.

## Tutorials: Same as before
Each tutorial contains text and code that explores various aspects of data science, replicability, and reproducibility. Tutorial 0 provides a gentle introduction to R for those with limited programming experience. Tutorials 1-4 contain questions to fill in, some require written answers and some require code to produce a plot or numerical summary.

* [`R_basics.Rmd`](https://github.com/areyesq89/PR2017replicaton/blob/master/R_basics.Rmd) : R markdown tutorial 0 - "R Basics"

* [`exploration.Rmd`](https://github.com/areyesq89/PR2017replicaton/blob/master/exploration.Rmd) : R markdown tutorial 1 - "What to do when you first get data"

* [`pharmaco_correlation.Rmd`](https://github.com/areyesq89/PR2017replicaton/blob/master/pharmaco_correlation.Rmd) : R markdown tutorial 2 - "Evaluating replicability of large pharmacological studies"

* [`targeted_therapies.Rmd`](https://github.com/areyesq89/PR2017replicaton/blob/master/targeted_therapies.Rmd) : R markdown tutorial 3 - "Identifying biological factors that influence replicability"

* [`regression.Rmd`](https://github.com/areyesq89/PR2017replicaton/blob/master/regression.Rmd) : R markdown tutorial 4 - "Regression approaches for summarizing drug response data"

## Code to generate data files (You do not need to use this): Same as before

For full reproducibility, this is the script to generate the csv files. This step has already been done for you.

* [`downloadData.R`](https://github.com/areyesq89/PR2017replicaton/blob/master/downloadData.R) : a script that uses the PharmacoGx package to format two datasets (raw and summary level) and save them as CSV files 

## Useful Links:

* [CCLE (Cancer Cell Line Encyclopedia) Study](https://www.ncbi.nlm.nih.gov/pubmed/22460905) from March 2012

* [GDSC (Genomics of Drug Sensitivity in Cancer) Study](https://www.ncbi.nlm.nih.gov/pubmed/22460902) from March 2012

* [Reanalysis of CCLE and GDSC](https://www.ncbi.nlm.nih.gov/pubmed/24284626) from December 2013

* [Commentary 1 on the reanalysis](https://www.ncbi.nlm.nih.gov/pubmed/27905415) from December 2016

* [Commentary 2 on the reanalysis](https://www.ncbi.nlm.nih.gov/pubmed/27905421) from December 2016

* [Commentary 3 on the reanalysis](http://www.nature.com/nature/journal/v540/n7631/full/nature20580.html) from December 2016
