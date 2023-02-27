# JGChIP_pipeline_v2

ChIPseq Analysis Pipeline

A ChIP-centric pipeline based on JBoyd's TAP pipeline and the ENCODE pipeline. Major variation is the use of Bowtie2, some different QC metrics and configurations.
 
Please see Github for most recent version (https://github.com/jgordon3/JGChIP_pipeline_V2)

# Basic Usage

This pipeline takes pairs of replicate ChIPseq data (fastqs) and:
   1) calculates raw sequencing metrics 
   2) performs alignment
   3) calculates QC metrics on indivdual replicates
   4) performs evaluation of replicates (correlation)
   5) combines replicates and calls peaks (to a cell specific input)
   6) generates bigwig, bigbed and UCSC tracks
   7) evaluates peaks to (sub)genomic location
   8) plots signals to features

![alt text](https://github.com/jgordon3/JGChIP_pipeline_v2/blob/[branch]/image.jpg?raw=true)     
