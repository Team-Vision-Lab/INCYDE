# INCYDE: INSAT-based Cyclone Detection and Intensity Estimation


# Cyclone Intensity Estimation Dataset

This repository contains the Cyclone Intensity Estimation Dataset, a collection of satellite images of cyclones captured by the INSAT satellite, along with corresponding intensity labels. The dataset was collected from the MOSDAC database.

## Dataset Details

- Total number of images: 98,466 (Intensity Estimation), 96,228 (Object Detection)
- Image resolution: 1616x1618 pixels
- Intensity range: 20 to 120 (MSWS)
- Date range: 08/10/2013 to 05/12/2021

## Download

The dataset is currently under review for the NeurIPS conference. Once the paper is accepted and the dataset is published, we will provide a download link in this section. Stay tuned!

## Dataset License

The Cyclone Intensity Estimation Dataset is distributed under the [Creative Commons Attribution 4.0 International (CC-BY) License](https://creativecommons.org/licenses/by/4.0/). Please see the [LICENSE](LICENSE) file for more details.

## Dataset DOI

If you use this dataset in your research or project, please cite it as follows:

[![DOI](https://zenodo.org/badge/DOI/10.1234/zenodo.123456789.svg)](https://doi.org/10.5281/zenodo.8015331)

## Example Usage

Here's an example code snippet demonstrating how to load and preprocess the dataset in Python:

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt

# Load dataset
data = pd.read_csv('dataset.csv')
images = data['image']
labels = data['intensity']

# Preprocess images
# ...

# Train your model
# ...

# Evaluate model performance
# ...
```
