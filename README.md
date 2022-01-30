# 🌬️ Zeph — Evaluation

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/dioptra-io/zeph-evaluation/HEAD)

This repository contains the code used to produce the results of the evalution section of the *Zeph & Iris* paper.

> When available: add plain text citation here.

The Python notebooks provided in this repository allow you to:
- perform your own measurements from the [Iris platform](https://iris.dioptra.io) to reproduce the dataset used in the paper
- reproduce the analysis presented in the paper, either on your own dataset, or on the original dataset used in the paper

In addition, the source code of Zeph and Iris are available in the [dioptra-io/zeph](https://github.com/dioptra-io/zeph) and [dioptra-io/iris](https://github.com/dioptra-io/zeph) repositories.

## 🧪 Experiments

Two notebooks are provided for each experiments: the *execution notebook* which contains the code to perform the measurements, and the *analysis notebook* which contains the code to analyse the measurement results and generate the plots.

To run these notebooks, copy the sample configuration file [`config/config.example.py`](config/config.example.py) to `config/config.py` and fill-in your Iris credentials.

If you want to run the analysis on the same dataset as used in the paper, download the following dataset from and extract it in the root directory of the repository in a directory named `resources`: [`zeph-evaluation-dataset.tar.gz`](https://minio.iris.dioptra.io/public/zeph-evaluation-dataset.tar.gz) (650MB).

### Experiment 1

> **Hypothesis**  
> Zeph will be able to see almost the same as complete discovery
(= full IPv4 routable prefixes) but with a much-reduced probing budget.


* Execution notebook: [exp1_experiment.ipynb](exp1_experiment.ipynb)
* Analysis notebook: [exp1_analysis.ipynb](exp1_analysis.ipynb)

### Experiment 2

> **Hypothesis**  
> For the same per-agent probing budget, allocating prefixes to agents based on an adaptive approach
(with the possibility of a prefix to be probed from any number from 0 to n agents)
will allow more to be discovered than allocating prefixes to agents randomly (with each prefix being probed from precisely one agent).

* Execution notebook: [exp2_experiment.ipynb](exp2_experiment.ipynb)
* Analysis notebook: [exp2_analysis.ipynb](exp2_analysis.ipynb)

### Experiment 3

> **Hypothesis**  
> Zeph will work at scale with Diamond-Miner. 

* Execution notebook: [exp3_experiment.ipynb](exp3_experiment.ipynb)
* Analysis notebook: [exp3_analysis.ipynb](exp3_analysis.ipynb)

### Exploitation analysis

> **Hypothesis**  
> The exploitation budget of Zeph will be responsible of the most part of nodes and links discoveries. 

* Execution notebook: based on one experiment of [exp1_experiment.ipynb](exp1_experiment.ipynb)
* Analysis notebook: [exploitation_analysis.ipynb](exploitation_analysis.ipynb)

## 📚 Publications

```
```
