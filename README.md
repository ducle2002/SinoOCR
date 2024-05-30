# Image Processing: Sino-Nom character localization

## Introduction

This project aims to localize Sino-Nom characters in images using image processing techniques and the YOLO (You Only Look Once) algorithm.

## Description

The project is structured as follows:

- `data.yaml`: Contains the configuration for the dataset.
- `datasets`: Contains the images and labels for training and validation.

## Repo Tree

```
.
├── datasets
│   ├── images              # Contain augmentated, train, validation images
│   └── labels              # Contain augmentated, train, validation labels
├── data.yaml
├── notebooks
│   └── augmentation.ipynb  # Experiments with augmentation
├── README.md
├── requirements.txt        # Dependencies to run included files in this repo
├── run.py
├── utils
│   ├── augmentation       # Implement image transformations
│   ├── dataset.py
│   └── __init__.py
└── yolo_baseline.py
```

## Result

With a strategy mainly focusing on data and taking advantage of famous existing architectures, our team had a model accuracy of 86.5% on the original val set
## Reproduce

To reproduce the results, follow the installation steps:

1. Install pip requirements
pip install -r requirements.txt
After the installation, you can start by running the training scripts provided and evaluate on your own data.

## Authors

This repository was made by my team consist of 4 members:
[Luu Van Duc Thieu](https://github.com/echodrift)
[Ngo Le Hoang](https://github.com/armistcxy)
[Nguyen Thanh Phat](https://github.com/aqu4holic)
[Le Hong Duc](https://github.com/tedomi2705)

## License

[MIT](https://choosealicense.com/licenses/mit/)

## Colab Notebook

You can also run the project in a Colab notebook: [Link](https://colab.research.google.com/drive/1cDcKd_3wE3Tx1GtuvY-uu9Q_HxoLI-3p?usp=sharing)
