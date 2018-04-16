# An Analysis of Kinetic Data

Raw data available comes in the form of time ordered quantities representing
intensity of fluorescence of calcium bound chromophore complexes within a cell.
The chromophore will only fluoresce when bound to calcium ions. It exists in
excess and thus probes the ion concentration within the cell. Ions enter the
cell via a key ion channel. The concentration of the ion as a function of time
is governed by the dynamics of the ion channel state-switching (binary on/off).
Rates of change and relative intensities will serve as the main analytical
quantities.


Main reports in [HTML](Ad-Trpm_R.html) and [Word](Ad-Trpm_R.docx)
formats are provided.

A [reproducibe analysis](Ad-Trpm_R.Rmd) is delivered as an R markdown file.  


# Getting Started
+ You will need to install [RStudio](https://www.rstudio.com/) to run the
R markdown (.Rmd) analysis files.
+ Launch RStudio and open the analysis file

# Developers
The project was developed with [miniconda](https://conda.io/miniconda.html).
+ Create an environment for the project using the provided environment.yml file.
```
conda env create
```
Now activate the environment and let's get started.
```
conda activate Ad-Trpm_R
```

create a text file to begin Rmarkdown
