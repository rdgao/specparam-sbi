# specparam-sbi
Tutorials on chaining together LFP simulation (`neurodsp`), spectral parameterization (`fooof`), and simulation-based inference (`sbi`).

|  Colab Link  |  Tutorial  |
| - | --- |
| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rdgao/specparam-sbi/blob/main/demo_notebooks/1-fooof_ndsp_demo.ipynb) |  **Demo 1**: minimal example of how to use `fooof` and simulating time series. |
| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rdgao/specparam-sbi/blob/main/demo_notebooks/2-EI.ipynb) |  **Demo 2**: reproducing the Poisson EI-1/f exponent model using `neurodsp`. |
| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rdgao/specparam-sbi/blob/main/demo_notebooks/3-sbi_demo.ipynb) |  **Demo 3**: minimal example of how to use `sbi`. |
| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rdgao/specparam-sbi/blob/main/demo_notebooks/4-EI_tau_inference.ipynb) |  **Demo 4**: combining everything to do inference and probabilistic spectral parameter estimation. |

Packages required (all installable via `pip install`):
- `neurodsp` ([repo](https://github.com/neurodsp-tools/neurodsp))
- `fooof` ([repo](https://github.com/fooof-tools/fooof))
- `sbi` ([repo](https://github.com/mackelab/sbi))
  
To set up and run in a new conda environment:
```
conda create -n sbsp python=3.8
conda activate sbsp
pip install uv
uv pip install jupyter fooof neurodsp sbi
```

For more complex mechanistic model simulations with spiking neural networks, go to [AutoMIND](https://github.com/mackelab/automind).
