Image Processing: Sino-Nom character localization
Introduction
This project aims to localize Sino-Nom characters in images using image processing techniques and the YOLO (You Only Look Once) algorithm.

Description
The project is structured as follows:

data.yaml: Contains the configuration for the dataset.
datasets: Contains the images and labels for training and validation.

Repo Tree
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
└── yolo_baseline.pyInstallation
To reproduce the results, follow the installation steps:
pip install -r requirements.txt
After the installation, you can start by running the training scripts provided and evaluate on your own data.

Result
With a strategy mainly focusing on data and taking advantage of famous existing architectures, our team had a model accuracy of 86.5% on the original val set
Contributors
Le Minh Duc-20020291
