# FIB-ADEI-LAB
Laboratori d'ADEI de la FIB

# Deliveables
## 1st deliverable - Data Processing, Description, Validation and Profiling

* Due Date October 18th, 2020 at 23:55 

### Things to deliever
* [PDF](https://atenea.upc.edu/mod/assign/view.php?id=2425736) Your assignment report is limited to 40 pages (an annex can be additionally included in the same document) and should be posted as a .pdf. PDF file name should be ClaudiaSanchez-JúliaGasull-Del1.pdf
* [Script/Rmarkdown and data](https://atenea.upc.edu/mod/assign/view.php?id=2425736) RScript/R Markdown has to be posted in ATENEA in the Task to Post Delivery I zip file for Script/Rmarkdown and data. 


### Outline of Deliverable I

#### Univariate Descriptive Analysis (to be included for each variable):
* Original numeric variables corresponding to qualitative concepts have to be converted to factors. New factors grouping original levels will be considered very positively.
* Original numeric variables corresponding to real quantitative concepts are kept as numeric but additional factors should also be created as a discretization of each numeric variable.
* Exploratory Data Analysis for each variables (numeric summary and graphic support).  

#### Data Quality Report:
* Per variable, count:
  * Number of missing values
  * Number of errors (including inconsistencies)
  * Number of outliers
  * Rank variables according the sum of missing values (and errors).

* Per individuals, count:
  * number of missing values
  * number of errors,
  * number of outliers
  * Identify individuals considered as multivariant outliers.

* Create variable adding the total number missing values, outliers and errors.

* Describe these variables, to which other variables exist higher associations.  
  * Compute the correlation with all other variables. Rank these variables according the correlation
  * Compute for every group of individuals (group of age, etc, …) the mean of missing/outliers/errors values. Rank the groups according the computed mean.

* Imputation:
  * Numeric Variables
  * Factors

Profiling:
  * Numeric Target (Total Amount)
  * Factor (Y.bin - Given Tip?)

*R Markdown script should be included in the .zip file to be posted. A report (pdf file) has to describe decisions, procedures, criteria, etc.*