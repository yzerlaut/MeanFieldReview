# Mean Field Review

**Code for simulations and analysis associated to the review:**

"_A general mean-field formalism for networks of spiking neurons, and its application to modeling brain activity at large scale_"  
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; by Y. Zerlaut and A. Destexhe

## Quick setup

1. Get a `python` distribution for scientific analysis from the anaconda website: either the latest [Anaconda](https://www.anaconda.com/products/distribution) or the [Miniconda](https://docs.conda.io/en/latest/miniconda.html#latest-miniconda-installer-links) distribution

2. Clone this repository by running the following command in the command prompt (either the UNIX shell prompt or the [Anaconda prompt](https://docs.anaconda.com/anaconda/user-guide/getting-started/#write-a-python-program-using-anaconda-prompt-or-terminal) on MS Windows*): 
```
git clone https://github.com/yzerlaut/MeanFieldReview
```

*On Ms Windows, `git` does not come by default and can be installed with `conda install git`.

3. Install the `reviewMF` environment:
```
cd MeanFieldReview
conda env create -f environment.yml
```

4. That's it ! From now, you should always activate the `reviewMF` environment before working with the code.  
This is done with the command:
```
conda activate reviewMF
```

## Tutorials

1. Full pipeline demo. Design the Mean-Field model for an excitatory/inhibitory network of AdExp neurons with conductance-based synapses.
2. Generalization to multiple populations.
3. 

## Manuscript content

We list here the content, ordered in terms of section 

### Introduction

[...]

### The Master Equation formalism

[...]








