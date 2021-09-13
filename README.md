# single-cell-LoH

### Project Summary
Yin Lab @UCLA project looking to visualize areas of Loss of Heterogeneity (LoH) using single-cell genomic data from 7702 *sgs1* yeast cells. 

### Lab Details
PI: Yi Yin 
Department: Human Genetics

### File Details

*\# of times a sgs1 position appears in ChrIV.csv*
- A comma-separated values file that contains a column of sgs1 positions on ChrIV and the number of times that position shows up as a SNP in the single-cell vcf files.

*\# of times each position is hetero in ChrIV.csv*
- A comma-separated values file that contains a column of sgs1 positions on ChrIV and the number of times that position is heterozygous in the single-cell vcf files.

### Folder Details

**Github:**
*ChrIV_Top 20 overrepresented hetero*: The files containing the YeastMine and SGD categorization of the 20 more overrepresented heterozygous positions SNP positions
*Figures*: Graphs and coverage plots generated from the code. 
*Misc*: Miscellaneous files that may be useful in the future
*notebooks*: 
- Arranged in the order that they were written. Contains all the main code generated for this project including all the code used to generate the plots and csv files.
- *Accessory functional ipynb* folder contains the other peripheral chunks of code used to generate or preprocess certain intermediate files. Useful if the reader wants to replicate with a differet set of similar files. 


*yeast_parent_vcf

**Google Drive**:[https://drive.google.com/drive/folders/1HIl4nvqCt4sGISSIpqAPKxpuDF3zcnnY?usp=sharing]
*Scoring Genotype by Region.zip*
- Contains all the intermediate data files (csv) and plots made by using Method A, B and C to generate the average psl2% in 6kbp and 15kbp windows  

*single cell aggregated data.zip*
- Contains aggregated data on each of the single-cell yeast files (~7700) including parameters such as whether the position is ref or alt, total number of reads, parent strain, psl2%, psl5% etc. 

*vcf.zip*
- Original unzipped single-cell files from source in the Variant Call Format. Unprocessed.

*tsv.zip*
- Original unprocessed vcf files converted to tab-separated values files (tsv) for ease of manipulation using Dataframes.


