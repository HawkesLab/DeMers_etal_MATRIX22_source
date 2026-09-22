# Data and Code from Phyllosphere flow: Microbial source-sink dynamics between wheat and field-adjacent plants 
# DeMers M, Willman M, Allen X, Heiniger R, Brown-Guedira G, Hawkes CV 

## Supplementary Data and Analysis
Data and analyses associated with this project.

## Experiment description
16S and ITS rRNA sequence analysis was used to characterize bacterial and fungal communities of Triticum aestivum leaves and leaves of plants near focal fields collected from 7 sites in North Carolina, USA. We analyzed community assembly based on host and sampling month, and source-sink dynamics between wheat and adjacent plants.

## File list  
### Data  
 ASV_counts_lulu_b.csv.zip  
 ASV_counts_lulu_f.csv.zip  
 ASV_taxonomy_lulu_b.csv  
 ASV_taxonomy_lulu_f.csv  
 ASVs_noCtls_b.fa.zip  
 ASVs_noCtls_f.fa  
 ISDs_b.fasta  
 ISDs_f.fasta  
 isd_match_list_b.txt  
 isd_match_list_f.txt  
 MATRIX22_16S_samdf.csv  
 MATRIX22_ITS_samdf.csv  
 sourcesink_b.zip  
 sourcesink_f.zip  
 

### Scripts and analyses  
 MATRIX_dataprep.Rmd - R markdown script to prepare data for analysis. Takes files after curation using mumu
 MATRIX_alphadiv.Rmd - R markdown script for analysis of community richness after data prep
 MATRIX_sourcesink.Rmd - R markdown script for analysis using SourceTracker. Requires only sourcesink zip files and downloading sourcetracker.r unless you want to do everything yourself.

## File descriptions  
### Data  

 ASV_counts_lulu_b.csv.zip + ASV_counts_lulu_f.csv.zip - ASV tables for bacterial and fungal communities after curation using mumu
 
 ASV_taxonomy_lulu_b.csv + ASV_taxonomy_lulu_f.csv - Table of taxonomic assignments for each ASV
 
 ASVs_noCtls_b.fa.zip + ASVs_noCtls_f.fa - Sequence for each ASV used for taxonomic assignments
 
 ISDs_b.fasta + ISDs_f.fasta - Sequences of synthetic internal standards used for normalization

 isd_match_list_b.txt + isd_match_list_f.txt - List of synthetic internal standard taxa for removal
 
 MATRIX22_16S_samdf.csv + MATRIX22_ITS_samdf.csv - Sample data tables containing information for each sample including plot, host, soil, and climate properties.  

 sourcesink_b.zip + sourcesink_f.zip - Bacterial and fungal ASV tables and metadata formatted for SourceTracker analyses

## Note  
Data files must be placed in your working directory for the analyses, or paths must be specified. Zipped data must be unzipped.

## Publication information  
TBD 

## Funding information  
This work was supported by funding from the Novo Nordisk Foundation (NNF19SA0059348) and by the Research Capacity Fund (HATCH; project award no. 7005451) from the U.S. Department of Agriculture’s National Institute of Food and Agriculture.

## Data availability    
Raw sequence data are in the NCBI SRA under BioProject PRJNA1255089
