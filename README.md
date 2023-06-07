# INCYDE: INSAT-based Cyclone Detection and Intensity Estimation


# Cyclone Intensity Estimation Dataset

This repository contains the Cyclone Intensity Estimation Dataset, a collection of satellite images of cyclones captured by the INSAT satellite, along with corresponding intensity labels. The dataset was collected from the MOSDAC database.

## Dataset Details

- Total number of images: XXXX
- Image resolution: XXXX pixels
- Intensity range: XX to XX (units)
- Date range: XX/XX/XXXX to XX/XX/XXXX

## Download

The dataset is currently under review for the NeurIPS conference. Once the paper is accepted and the dataset is published, we will provide a download link in this section. Stay tuned!

## Dataset License

The Cyclone Intensity Estimation Dataset is distributed under the [Creative Commons Attribution 4.0 International (CC-BY) License](https://creativecommons.org/licenses/by/4.0/). Please see the [LICENSE](LICENSE) file for more details.

## Citation

If you use this dataset in your research or project, please cite it as follows:

Author Name. (Year). Cyclone Intensity Estimation Dataset. In Proceedings of the Conference Name (NeurIPS Year), pages XXXX-XXXX.

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

## Contact

For any questions or inquiries regarding the dataset, please contact the authors:

- Author 1:
  - Name: Author 1 Name
  - Email: author1@example.com

- Author 2:
  - Name: Author 2 Name
  - Email: author2@example.com
