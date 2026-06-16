Physcomitrium Gene Mapping Pipeline

This repository contains scripts and workflows for gene mapping in Physcomitrium patens, including read mapping, variant calling, and bulked segregant analysis (BSA).

Contents
Linux shell scripts (.ipynb): used for read mapping, variant calling, sequence processing, and other bioinformatic analyses.
BSA scripts (.qmd): implemented in R for linkage analysis.
HTML files: rendered outputs generated from the corresponding Markdown files (.qmd and .ipynb) for easier viewing.
VCF files (and vcf index): required in this workflow.
Reference genome files should be downloaded by users (Ppatens_870_V6.fasta and Ppatens_870_v6.1.gene.gff3)

Requirements
Linux environment for shell scripts
R (version ≥ 4.0 recommended) for BSA analysis
Required bioinformatics software as specified in individual scripts

Citation
If you use these scripts or workflows in your research, please cite the corresponding publication(s) where appropriate.

Notes
These scripts were developed for gene mapping in Physcomitrium patens and may require modification for use with other species or experimental designs.