# Hasdeo Deforestation Detection Study

This project trains an attention U-Net model to detect forest cover and estimate deforestation trends in the Hasdeo-Arand region using annual GeoTIFF imagery.

## Setup

1. Create and activate a Python environment.
2. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Download the dataset from Kaggle:
   https://www.kaggle.com/datasets/gauravkhakse/hasdeo-deforestation-detection-study/data
4. Copy the annual GeoTIFF files into `data/`.

## Input Data

The notebook expects these files in `data/`:

- `2018.tif`
- `2019.tif`
- `2020.tif`
- `2021.tif`
- `2022.tif`
- `2023.tif`
- `2024.tif`

## Run

Open `Hasdeo_training.ipynb` and run the cells in order.

## Outputs

Results are written to `hasdeo_outputs/`, including:

- trained model files
- patch index files
- validation metrics
- yearly forest coverage tables
- deforestation summary tables
- prediction rasters and change maps

## Notes

The notebook uses `./data` as its input directory and `./hasdeo_outputs` for generated results.