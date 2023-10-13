# specparam-sbi
Tutorials on chaining together LFP simulation (`neurodsp`), spectral parameterization (`fooof`), and simulation-based inference (`sbi`).

<a target="_blank" href="https://colab.research.google.com/github/rdgao/specparam-sbi/blob/main/demo_notebooks/1-fooof_ndsp_demo.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

**Demo 1**: minimal example of how to use `fooof` and simulating time series.
<br>

<a target="_blank" href="https://colab.research.google.com/github/rdgao/specparam-sbi/blob/main/demo_notebooks/2-EI.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a> 

**Demo 2**: reproducing the Poisson EI-1/f exponent model using `neurodsp`.
<br>


<a target="_blank" href="https://colab.research.google.com/github/rdgao/specparam-sbi/blob/main/demo_notebooks/3-sbi_demo.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a> 

**Demo 3**: minimal example of how to use `sbi`.
<br>


<a target="_blank" href="https://colab.research.google.com/github/rdgao/specparam-sbi/blob/main/demo_notebooks/4-EI_tau_inference.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

**Demo 4**: combining everything to do inference and probabilistic spectral parameter estimation.
<br>
<br>

Packages required (all installable via `pip install`):
- `neurodsp` ([repo](https://github.com/neurodsp-tools/neurodsp))
- `fooof` ([repo](https://github.com/fooof-tools/fooof))
- `sbi` ([repo](https://github.com/mackelab/sbi))
  
Should already have as dependencies:
- `jupyter`
- `matplotlib`
- `numpy`
- `scipy`
