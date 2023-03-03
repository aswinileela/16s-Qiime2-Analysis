# 16s-Qiime2-Analysis

### Download latest version of Qiime2(Linux)

wget https://data.qiime2.org/distro/core/qiime2-2023.2-py38-linux-conda.yml

### Create conda environment and install Qiime2
conda env create -n qiime2-2023.2 --file qiime2-2023.2-py38-linux-conda.yml

### Activate conda environment

conda activate qiime2-2023.2

### Test the Installation

qiime --help

### To run the pipeline

bash 16s.sh

### Resources

https://docs.qiime2.org/2020.11/tutorials/moving-pictures/

http://compbio.ucsd.edu/wp-content/uploads/2016/10/20170712_microbiome_16s_tutorial_non-interactive.pdf

https://docs.qiime2.org/2020.11/tutorials/overview/
