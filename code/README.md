This folder contains three subfolders:

* _notebooks_, which contains the code (as Jupyter Notebooks) for our experiments;
* _figures_, which contains the figures produced by running our code, and included in our paper and supplementary material;
* _results_, which contains files (as "pickles") having the complete results of our evaluation. To visualize these, you just need to load the pickles and inspect them  (refer to the corresponding notebook) 

### Setup

For replicating our experiments, we first recommend to ensure that your environment matches the one used for our evaluation: you can see the libraries and specifications in the "test_and_specs.ipynb" notebook.

### Data

We also endorse you to obtain the dataset we used for our experiments, which can be retrieved by the official Mendeley [repository](https://data.mendeley.com/datasets/h3cgnj8hft/1), which is related to the [paper by Chiew et al](https://www.sciencedirect.com/science/article/abs/pii/S0020025519300763). For convenience, we are providing the dataset here ("mendeley.arff") to kickstart your experiments.

### Disclaimer

We repeat our experiments many times, but randomness plays an important role in ML evaluations: hence, the code may yield slightly different results than the ones reported in our paper.