# TFRS

## Install in M1
```
conda env create -f tensorflow-apple-metal-conda.yml -n tfrs
conda activate tfrs
python -m pip install --force-reinstall --no-deps tensorflow-recommenders
python -m pip install tensorflow-datasets
```