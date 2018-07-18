# Nanopore snp-pipeline
A simple SNP pipeline optimized for Nanopore RNA-Sequencing data. 
This is a bash script where different filter preferences may be applied by changing the values for the variables in lines 3-10. 
Three files are needed for this program to run: SAM file (with header), reference genome (.fa format), and SNP database (.vcf or .vcf.gz). 
All files must be in the same directory.
Up to four filters may be applied: map quality, base qaulity, variant quality, and depth filtering. 
Suggested filters for Nanopore data are found in the wiki. However, this pipeline may be used for any SNP calling data with mindful changes to the filters. 
