### Included Functionalities

The notebook contains the following components:

* Importing required libraries
* Dataset loading
* Dataset preprocessing
* Image resizing and normalization
* Train, validation, and test data splitting
* Data augmentation
* CNN model development
* CNN model training
* Model evaluation
* Confusion matrix generation
* Classification report generation
* Transfer learning using MobileNetV2
* Model comparison
* Saving figures and tables

### Required Python Libraries

```python
import os
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

from sklearn.model_selection import train_test_split
from sklearn.metrics import classification_report, confusion_matrix

import tensorflow as tf
from tensorflow.keras.preprocessing.image import ImageDataGenerator
from tensorflow.keras.models import Sequential
from tensorflow.keras.layers import Conv2D, MaxPooling2D, Flatten
from tensorflow.keras.layers import Dense, Dropout, BatchNormalization
from tensorflow.keras.applications import MobileNetV2
from tensorflow.keras.models import Model
from tensorflow.keras.layers import GlobalAveragePooling2D
from tensorflow.keras.optimizers import Adam
```

The notebook is fully self-contained and can be executed from start to finish to reproduce all experiments, figures, tables, and evaluation results presented in this project.
