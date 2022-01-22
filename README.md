#### To install & activate the environment:

```
conda create -n dvc-example python=3.9
conda activate dvc-example
conda install -c conda-forge jupyterlab jupyterlab_vim ipywidgets jupyterlab_code_formatter black isort -y
pip install nb_black dvc
```

#### To run the notebook:

`jupyter lab`

#### If you can't find the kernel

```
conda install nb_conda_kernels -y && ipython kernel install --user --display-name $CONDA_DEFAULT_ENV --name $CONDA_DEFAULT_ENV
```

Then you should able to select the `dvc-example` kernel
