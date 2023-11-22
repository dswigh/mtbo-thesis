# mtbo-thesis

This repository contains all the code necessary to reproduce the results presented in the Multi-task Bayesaion optimisation chapter of my thesis.

Initially forked from an older version of sre/multitask, it also represents my contributions to the MTBO conference paper and journal article.



## Relevant References

- [Fast continuous alcohol amination employing a hydrogen borrowing protocol](https://pubs.rsc.org/en/content/articlelanding/2019/gc/c8gc03328e#!divAbstract)
- [A Survey of the Borrowing Hydrogen Approach to the Synthesis of some Pharmaceutically Relevant Intermediates](https://pubs.acs.org/doi/10.1021/acs.oprd.5b00199)
- [Multi-task Bayesian Optimization of Chemical Reactions](https://chemrxiv.org/articles/preprint/Multi-task_Bayesian_Optimization_of_Chemical_Reactions/13250216)
- Worth reading through the [peer review](https://static-content.springer.com/esm/art%3A10.1038%2Fs41586-021-03213-y/MediaObjects/41586_2021_3213_MOESM2_ESM.pdf) of the shields Nature paper.
- [Baumgartner C-N](https://pubs.acs.org/doi/10.1021/acs.oprd.9b00236): 4 cases with varying catalysts, bases, temperature, residence time, base equivalents and optimizing yield and TON


## Setup

Clone the project:

    git clone https://github.com/sustainable-processes/multitask.git

Install [poetry](https://python-poetry.org/docs/) and then run the following command to install dependencies:

    poetry install

Code in notebooks should be fairly self-explanatory. All figures used in the MTBO chapter of the thesis can be found in the figures folder.

