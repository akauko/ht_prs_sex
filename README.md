# ht_prs_sex
Code for the publication: Kauko, Anni, et al. "Sex differences in genetic risk for hypertension." Hypertension 78.4 (2021): 1153-1155.
https://doi.org/10.1161/hypertensionaha.121.17796

* Data: FinnGen (https://www.finngen.fi/en)
* PRS values were calculuted for FinnGen individuals using PRS-CS pipeline with default settings: https://github.com/getian107/PRScs
* We used GWAS summaries from UKBB GWAS v3: https://docs.google.com/spreadsheets/d/1kvPoupSzsSFBNSztMzl04xMoSC3Kcx3CrjVf4yBmESU/edit#gid=227859291

```
ht_prs_sex
├── README.md                 	# Overview
├── ht_prs_sex.rmd            	# R markdown for the analysis
├── Functions.R      	      	# Minor R functions for the main analysis
├── select_columns.pl         	# Perl script to select columns from tsv files by column name

```
