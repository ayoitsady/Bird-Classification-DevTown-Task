# Bird Species Image Classification

Welcome to the Bird Species Image Classification project repository! This Python notebook focuses on leveraging machine learning algorithms for the image classification task of identifying 525 different bird species. The goal is to accurately categorize and classify birds based on a dataset of images using advanced algorithms.

## About the Dataset

The dataset comprises 525 bird species, with a meticulously cleaned set of 84,635 training images, 2,625 test images (5 images per species), and 2,625 validation images (5 images per species). Rigorous cleaning processes have eliminated duplicate and near-duplicate images, ensuring dataset integrity and preventing leakage between training, test, and validation sets.

### Dataset Characteristics:

- **Image Format:** JPG
- **Image Size:** 224 x 224 x 3 pixels
- **Species Distribution:** The training set exhibits an unbalanced distribution, with a minimum of 130 training images per species.
- **Gender Bias:** Approximately 80% of the images depict males, while 20% depict females.
- **Metadata:** The "birds.csv" file provides essential metadata, including file paths, labels, scientific names, and dataset designations.

### Note:

- **Unbalanced Distribution:** Due to the varying number of training images per species, the dataset might exhibit class imbalance.
- **Gender Bias Impact:** Classifier performance may vary between male and female species images due to the gender distribution in the dataset.
- **Image Size for Training:** To expedite model training, a reduced image size of 150 x 150 x 3 pixels is recommended.

## Getting Started

### Prerequisites

Before running the notebook, ensure you have the following dependencies installed:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn tensorflow
```

### Steps to Run the Notebook
1. Clone this repository to your local machine:

```bash
git clone https://github.com/Harbringe/bird-classification/
```
2. Navigate to the project directory:
```bash
cd bird-classification
```
3. Download the dataset using the provided link and place it in the project directory.

4. Open and run the "bird-classification.ipynb" notebook using Jupyter Notebook or Jupyter Lab:

```bash
jupyter notebook bird_classification.ipynb
```
Follow the instructions in the notebook to execute each cell.

## Acknowledgments

This project aims to contribute to the field of image classification, particularly in the domain of bird species identification. Feel free to explore, contribute, and enhance the model for further applications.

Happy classifying!

[Download Dataset](https://www.kaggle.com/datasets/gpiosenka/100-bird-species)

