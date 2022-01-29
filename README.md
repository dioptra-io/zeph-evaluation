# 🌬️ Zeph - Paper evaluation

This is the scripts for used for the evaluation section of [Zeph](https://github.com/dioptra-io/zeph)'s paper.  
With this repository you are able to: 
* recreate your own dataset of the experiments on [Iris](https://github.com/dioptra-io/iris)
* replicate the results of the paper by running the analysis scripts on your dataset or on the dataset used in the paper

## 🧪 Experiments

In order to run the experiments and the analysis, simply copy the configuration example from `config/config.example.py` to `config/config.py`
and add your Iris credentials in the new created file.  
Optionnaly, you can change the iris URL to use your own Iris instance. 

If you want to run the analysis on the same dataset used in the papier, download the dataset from [here](https://minio.iris.dioptra.io/public/zeph-evaluation-dataset.tar.gz) and extract it in the root directory of the repository with the name `resources`.

### Experiment 1

*Hypothesis*: Zeph will be able to see almost the same as complete discovery
(= full IPv4 routable prefixes) but with a much-reduced probing budget.

* Execution notebook: [exp1_experiment.ipynb](exp1_experiment.ipynb)
* Analysis notebook: [exp1_analysis.ipynb](exp1_analysis.ipynb)

### Experiment 2

*Hypothesis*: for the same per-agent probing budget, allocating prefixes to agents based on an adaptive approach
(with the possibility of a prefix to be probed from any number from 0 to n agents)
will allow more to be discovered than allocating prefixes to agents randomly (with each prefix being probed from precisely one agent).

* Execution notebook: [exp2_experiment.ipynb](exp2_experiment.ipynb)
* Analysis notebook: [exp2_analysis.ipynb](exp2_analysis.ipynb)

### Experiment 3

*Hypothesis*: Zeph will work at scale with Diamond-Miner. 

* Execution notebook: [exp3_experiment.ipynb](exp3_experiment.ipynb)
* Analysis notebook: [exp3_analysis.ipynb](exp3_analysis.ipynb)

### Exploitation analysis

*Hypothesis*: the exploitation budget of Zeph will be responsible of the most part of nodes and links discoveries. 

* Execution notebook: based on one experiment of [exp1_experiment.ipynb](exp1_experiment.ipynb)
* Analysis notebook: [exploitation_analysis.ipynb](exploitation_analysis.ipynb)

## 📚 Publications

```
```
