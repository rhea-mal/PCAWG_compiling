# PCAWG_compiling
select bulk whole genome sequencing data from PCAWG consortium

These notebooks assemble selected samples into a single table from the Pan Cancer Analysis of Whole Genomes (PCAWG) Consortium.
These notebooks specificlaly select for ovarian cancer (OV-US) of High Grade Serous Ovarian Carcinoma and Triple Negative Breast Cancer (TNBC). The data can also be filtered by star score for accuracy. The read counts are then binned for use in comparison to simulated read count data.

Download from repositories linked below.
PCAWG: https://dcc.icgc.org/pcawg

In order to run assemble_PCAWGtables.Rmd and mergetxts.Rmd, download the consensus_cnv folder from the PCAWG open source repository. 
