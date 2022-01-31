# 🌬️ Zeph — Evaluation

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/dioptra-io/zeph-evaluation/HEAD)

This repository contains the code used to produce the results of the evalution section of the *Zeph & Iris* paper.

The Python notebooks provided in this repository allow you to:
- perform your own measurements from the [Iris platform](https://iris.dioptra.io) to reproduce the dataset used in the paper
- reproduce the analysis presented in the paper, either on your own dataset, or on the original dataset used in the paper

In addition, the source code of Zeph and Iris are available in the [`dioptra-io/zeph`](https://github.com/dioptra-io/zeph) and [`dioptra-io/iris`](https://github.com/dioptra-io/iris) repositories.

## 🧪 Experiments

### Prerequisites

1. Copy the sample configuration file [`config.example.json`](config.example.json) to `config.json` and fill-in your Iris credentials.
2.  Download [`zeph-evaluation-dataset.tar.gz`](https://minio.iris.dioptra.io/public/zeph-evaluation-dataset.tar.gz) (650MB) and extract it at the root of the repository:
```bash
wget https://minio.iris.dioptra.io/public/zeph-evaluation-dataset.tar.gz
tar xf zeph-evaluation-dataset.tar.gz
```

### Notebooks

Two notebooks are provided for each section: the *execution notebook* which contains the code to perform the measurements, and the *analysis notebook* which contains the code to analyse the measurement results and generate the plots.

Section | Execution | Analysis
--------|-----------|---------
§6.2.1 — Zeph's reinforcement learning approach outperforms random allocation | [`zeph_allocation_execution.ipynb`](notebooks/zeph_allocation_execution.ipynb) | [`zeph_allocation_analysis.ipynb`](notebooks/zeph_allocation_analysis.ipynb)
§6.2.2 — Zeph/Iris conducting multipath traceroutes performs competitively with respect to current state-of-the-art internet scale topology discovery systems | [`zeph_topology_execution.ipynb`](notebooks/zeph_topology_execution.ipynb) | [`zeph_topology_analysis.ipynb`](notebooks/zeph_topology_analysis.ipynb)
§6.3 — Zeph probe savings | [`zeph_savings_execution.ipynb`](notebooks/zeph_savings_execution.ipynb) | [`zeph_savings_analysis.ipynb`](notebooks/zeph_savings_analysis.ipynb)
§6.4 — Reinforcement learning analysis | [`zeph_savings_execution.ipynb`](notebooks/zeph_savings_execution.ipynb) | [`rl_analysis.ipynb`](notebooks/rl_analysis.ipynb)

## 📚 Publications

```
```
