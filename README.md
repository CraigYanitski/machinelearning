# Machine learning

This is a repository to collect tutorials/examples of machine learning (ML), deep learning (DL), and maybe even artificial intelligence (AI, we will not touch AGI). The aim is to provide a better intuition of the benefits and constraints to implementing ML for a given problem. Hopefully this will give us a more fundamental understanding of what happens "behind the scenes". This will be developed over time to explain most of the methods of ML, DL, and AI, as well as possibly implementing new features.

 > *Note: these examples will be written entirely in **python** utilising `jupyter` notebooks.*

## Environment setup

You can load the environment using,

```
git clone https://github.com/CraigYanitski/machinelearning.git
```

For python, hopefully you have installed either anaconda or miniconda. If you `cd` to the repo directory, you can then install an environment for this repo using the environment file:

```
conda install mamba -n base -c conda-forge
mamba env create -f environment.yml
conda activate machinelearning
```

and you can keep the environment up-to-date with,

```
conda activate machinelearning
mamba env update -f environment.yml
```