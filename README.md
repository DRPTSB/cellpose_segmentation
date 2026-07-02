# cellpose_segmentation

Minimal repository backbone for running Cellpose-based image segmentation in notebooks.

## Repository layout

- `notebooks/` for exploratory notebooks
- `environment.yml` for the Python environment

## Getting started

Create the environment:

```bash
conda env create -f environment.yml
conda activate cellpose-segmentation
python -m ipykernel install --user --name cellpose-segmentation
```

Launch notebooks:

```bash
jupyter lab
```
