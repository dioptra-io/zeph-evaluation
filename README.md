# 🌬️ Zeph - Paper evaluation

This is the evaluation scripts for [Zeph](https://github.com/dioptra-io/zeph) used for the evaluation section of the paper.  
You can replicate the results of the paper by running the analysis scripts with your Iris credentials on the same dataset.  
You can also create your own dataset by running the experiment scripts with your Iris credentials.

# 🧪 Experiments

In order to run the experiments, simply copy the configuration example to `config/config.py`
and add your Iris credentials in the new create file. 

## Experiment 1

*Hypothesis*: Zeph will be able to see almost the same as complete discovery
(= full IPv4 routable prefixes) but with a much-reduced probing budget.

* Execution notebook: [exp1_experiment.ipynb](exp1_experiment.ipynb)
* Analysis notebook: [exp1_analysis.ipynb](exp1_analysis.ipynb)

## Experiment 2

*Hypothesis*: for the same per-agent probing budget, allocating prefixes to agents based on an adaptive approach
(with the possibility of a prefix to be probed from any number from 0 to n agents)
will allow more to be discovered than allocating prefixes to agents randomly (with each prefix being probed from precisely one agent).

* Execution notebook: [exp2_experiment.ipynb](exp2_experiment.ipynb)
* Analysis notebook: [exp2_analysis.ipynb](exp2_analysis.ipynb)

## Experiment 3

*Hypothesis*: Zeph will work at scale with Diamond-Miner. 

* Execution notebook: [exp3_experiment.ipynb](exp3_experiment.ipynb)
* Analysis notebook: [exp3_analysis.ipynb](exp3_analysis.ipynb)

## Exploitation analysis

*Hypothesis*: the exploitation budget of Zeph will be responsible of the most part of nodes and links discoveries. 

* Analysis notebook: [exploitation_analysis.ipynb](exploitation_analysis.ipynb)

## 📚 Publications

```
```
