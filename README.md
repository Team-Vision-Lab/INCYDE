# INCYDE: INSAT-based Cyclone Detection and Intensity Estimation


# Cyclone Intensity Estimation Dataset

INCYDE (INSAT-based Cyclone Detection and Intensity Estimation) is a cyclone detection and intensity estimation dataset. The cyclone images in the dataset are captured from INSAT 3D/3DR satellites over the Indian Ocean. The proposed INCYDE dataset contains over 100k cyclone images with augmentations taken from cyclones over the Indian Ocean from the year 2013 to 2021. The dataset pertains to two specific tasks: cyclone detection as an object detection task, and intensity estimation as a regression task. In addition to the dataset, this study introduces baseline models that were trained on the newly presented dataset

## Dataset Details

- Total number of images: 98,466 (Intensity Estimation), 96,228 (Object Detection)
- Image resolution: 1616x1618 pixels
- Intensity range: 20 to 120 (MSWS)
- Date range: 08/10/2013 to 05/12/2021

## Download

The dataset is currently under review for the NeurIPS conference. Once the paper is accepted and the dataset is published, we will provide a download link in this section. Stay tuned!

## Dataset License

The Cyclone Intensity Estimation Dataset is distributed under the [Creative Commons Attribution-NonCommercial 4.0 International](https://creativecommons.org/licenses/by-nc/4.0/).
## Dataset DOI

If you use this dataset in your research or project, please cite it as follows:

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.8015544.svg)](https://doi.org/10.5281/zenodo.8015544)

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
