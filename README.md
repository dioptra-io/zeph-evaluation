## Important Notice
**DUE TO SUPPORT ISSUES, THE IRIS SYSTEM IS NO LONGER AVAILABLE AS A
PUBLIC SERVICE FOR RUNNING INDEPENDENT MEASUREMENTS.
HOWEVER, IRIS DATA CONTINUES TO BE PUBLISHED AND IS ACCESSIBLE TO
THE PUBLIC VIA [M-LAB](https://www.measurementlab.net).
FOR MORE INFORMATION, PLEASE VISIT [IPRS](https://iprs.dioptra.io).**

# 🌬️ Zeph — Evaluation

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/dioptra-io/zeph-evaluation/HEAD)

This repository contains the code used to generate the results
presented in the evaluation section of the *Zeph & Iris* paper.
Please note, however, that the current versions of Zeph and Iris
available in the [`dioptra-io/zeph`](https://github.com/dioptra-io/zeph)
and [`dioptra-io/iris`](https://github.com/dioptra-io/iris)
repositories, differ from the exact versions used in the paper. If
you require the specific commit SHA1s corresponding to the versions
used in the publication, feel free to open an issue.

You can download Iris source code and run your own instance of Iris
but please note that we are unable to provide support.

## 🧪 Experiments

### Prerequisites

1. Set up your own Iris instance.
2. Download [`zeph-evaluation-dataset.tar.gz`](https://github.com/dioptra-io/zeph-evaluation/releases/tag/v1.0.0).

### Notebooks

Two notebooks are provided for each section: the *execution notebook* which contains the code to perform the measurements, and the *analysis notebook* which contains the code to analyse the measurement results and generate the plots.

Section | Execution | Analysis
--------|-----------|---------
§6.2.1 — Zeph's reinforcement learning approach outperforms random allocation | [`zeph_allocation_execution.ipynb`](notebooks/zeph_allocation_execution.ipynb) | [`zeph_allocation_analysis.ipynb`](notebooks/zeph_allocation_analysis.ipynb)
§6.2.2 — Zeph/Iris conducting multipath traceroutes performs competitively with respect to current state-of-the-art internet scale topology discovery systems | [`zeph_topology_execution.ipynb`](notebooks/zeph_topology_execution.ipynb) | [`zeph_topology_analysis.ipynb`](notebooks/zeph_topology_analysis.ipynb)
§6.3 — Zeph probe savings | [`zeph_savings_execution.ipynb`](notebooks/zeph_savings_execution.ipynb) | [`zeph_savings_analysis.ipynb`](notebooks/zeph_savings_analysis.ipynb)
§6.4 — Reinforcement learning analysis | [`zeph_savings_execution.ipynb`](notebooks/zeph_savings_execution.ipynb) | [`rl_analysis.ipynb`](notebooks/rl_analysis.ipynb)

## 📚 Publications

```bibtex
@article{10.1145/3523230.3523232,
author = {Gouel, Matthieu and Vermeulen, Kevin and Mouchet, Maxime and Rohrer, Justin P. and Fourmaux, Olivier and Friedman, Timur},
title = {Zeph &amp; Iris Map the Internet: A Resilient Reinforcement Learning Approach to Distributed IP Route Tracing},
year = {2022},
issue_date = {January 2022},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
volume = {52},
number = {1},
issn = {0146-4833},
url = {https://doi.org/10.1145/3523230.3523232},
doi = {10.1145/3523230.3523232},
journal = {SIGCOMM Comput. Commun. Rev.},
month = {mar},
pages = {2–9},
numpages = {8},
keywords = {active internet measurements, internet topology}
}
```
