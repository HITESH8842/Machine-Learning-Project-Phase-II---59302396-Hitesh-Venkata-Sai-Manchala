## Instructions for Running the Code

### 1. Clone or Download the Repository

Download the project files from GitHub or clone the repository:

```bash
git clone <repository-link>
```

### 2. Install Required Libraries

Install all required Python packages using:

```bash
pip install -r requirements.txt
```

### 3. Download the Dataset

Download the Fashion Product Images Dataset from Kaggle:

https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-dataset

Extract the dataset and place the following files inside the `Data` folder:

```text
Data/
├── styles.csv
└── images/
```

### 4. Update Dataset Paths

Open the notebook and modify the dataset paths according to your local system:

```python
CSV_PATH = "Data/styles.csv"
IMAGE_FOLDER = "Data/images"
```

### 5. Launch Jupyter Notebook

Start Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
Fashion_Attribute_Recognition_Using_CNNs.ipynb
```

### 6. Run the Notebook

Execute all cells sequentially from top to bottom:

1. Import Libraries
2. Dataset Loading
3. Dataset Preprocessing
4. Train/Validation/Test Split
5. Data Augmentation
6. CNN Model Development
7. CNN Model Training
8. Model Evaluation
9. Confusion Matrix
10. Classification Report
11. Transfer Learning (MobileNetV2)
12. Model Comparison
13. Save Figures and Tables

### 7. Output Files

After execution, the notebook will generate:

```text
Figures/
├── cnn_accuracy_curve.png
├── cnn_loss_curve.png
├── cnn_confusion_matrix.png

Tables/
├── classification_report.csv
├── cnn_evaluation_metrics.csv
└── model_comparison_table.csv
```

### 8. System Requirements

* Python 3.10 or later
* Jupyter Notebook
* TensorFlow
* Keras
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

### Notes

* Ensure that the dataset paths are correctly configured before running the notebook.
* Running the notebook may take several minutes depending on system specifications and dataset size.
* A GPU is recommended for faster model training but is not required.
