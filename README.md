If you haven't already, please install [Anaconda](https://www.anaconda.com/distribution/).

To get started with the `lab.ipynb` notebook, create an environment using the `dependencies.yml` file:

```bash
conda env create --file dependencies.yml
conda activate cdo
ipython kernel install --name=cdo
```

Then launch `jupyter lab` in your terminal. Once launched, open the `lab.ipynb` and select `Kernel -> Change kernel -> Python [conda env:cdo]`.
