# snp-pipeline
A simple SNP pipeline optimized for Nanopore RNA-Sequencing data. 
This is a command line code that prompts for certain filter preference. 
Three files are needed for this program to run: SAM file (with header), reference genome (.fa format), and SNP database (.vcf or .vcf.gz). 
All files must be in the same directory.
Up to four filters may be applied: map quality, base qaulity, variant quality, and depth filtering. 
