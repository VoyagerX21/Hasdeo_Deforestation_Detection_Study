# Hasdeo-Arand Forest Dataset

This folder must contain the annual GeoTIFF inputs used by the training notebook.

## Required Files

Place the following files directly in this folder:

- `2018.tif`
- `2019.tif`
- `2020.tif`
- `2021.tif`
- `2022.tif`
- `2023.tif`
- `2024.tif`

## Download and Setup

1. Download the Kaggle dataset from:
	https://www.kaggle.com/datasets/gauravkhakse/hasdeo-deforestation-detection-study/data
2. Extract the archive.
3. Copy the annual GeoTIFF files into this `data/` folder.
4. Confirm the files are named exactly as listed above.

## Use in the Notebook

The notebook reads these files from `./data`.

## Output Files

The notebook writes predictions and summary artifacts to `./hasdeo_outputs`.