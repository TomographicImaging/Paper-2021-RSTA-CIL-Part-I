This code reproduces all the results presented in 

[**Core Imaging Library part I: a versatile python framework for tomographic imaging**](https://doi.org/10.1098/rsta.2020.0192).

A preprint is available from arXiv:

https://arxiv.org/abs/2102.04560

# Instructions

## 1) **Install the environment**

**Note:** Depending on your nvidia-drivers, you can modify the `cudatoolkit` parameter. See [here](https://docs.nvidia.com/deploy/cuda-compatibility/index.html) for more information.

```bash
conda create --name cil1_demos -c conda-forge -c astra-toolbox/label/dev -c ccpi cil cil-astra ccpi-regulariser nb_conda_kernels jupyterlab cudatoolkit=_._
```      

## 2) **Activate the environment**

```bash
conda activate cil1_demos
```

## 3)
There are four Jupyter notebooks caseXX_... for XX = 00, 01, 02, 03 covering the running example and the three case studies of the article. The steel-wire dataset of the running example is included in CIL. The case study datasets are available as detailed in the article. Each notebook runs all processing and reconstruction and produces the figures (and more) as shown in the article.


    
# Reference
    
Jørgensen JS et al. 2021 Core Imaging Library part I: a versatile python framework for tomographic imaging. Phil. Trans. R. Soc. A 20200192.           (https://doi.org/10.1098/rsta.2020.0192)

