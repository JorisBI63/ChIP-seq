# ChIP-seq
Workflow for ChIP-sequencing processing

## Install tools for the pipeline
Create a conda environment on your server which you can call ChIP-seq environment.

`conda create -n chipseq`

activate the environment:

'conda activate chipseq`

Install fastqc (quality control):
`conda install bioconda::fastqc` 

Install bbmap (trimming):
`conda install bioconda::bbmap`



## Processing 

1) Trimming reads
2) Mapping reads
3) Filter mapping reads
4) Peaks calling




### 1.Trimming 

`bash trim .sh` 


## Visualization 

