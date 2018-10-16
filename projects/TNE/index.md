---
layout: tne
---
# Description

# Code
##### Installation
> git clone https://github.com/abdcelikkanat/TNE.git

It may be required to compile "word2vec_inner.pyx" file.

##### Installation with Anaconda
Create a conda environment named 'tne'
> conda create -n tne python=3.5

Activate the conda environment
> source activate tne

Run the following command to install the required packages
> pip install -r requirements.txt

#### Usage
##### Example

To test TNE on Zachary's karate club network, run the following commands from the project home directory.
> source activate tne

> python run.py --graph_path ./datasets/karate.gml --random_walk deepwalk --n 80 --l 10 --k 2 --community_detection_method lda --negative 5 --output_folder ./outputs --concat_method max

##### Options

You can see the other available options by invoking the command:
> python run.py --help


### Experiments
