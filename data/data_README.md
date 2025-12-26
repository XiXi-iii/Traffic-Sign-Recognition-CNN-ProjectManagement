# Dataset Information

## Source
The dataset used in this project is the **German Traffic Sign Recognition Benchmark (GTSRB)**.
* **Download Link:** [https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign]

## Setup Instructions
Due to GitHub's file size limits, the raw `.tar` or `.zip` files are not included in this repository. To run the training or demo scripts:
1. Download the dataset from the link above.
2. Extract the files.
3. Place the `Train` and `Test` folders inside this `/data` directory.

## Dataset Specifications
* **Total Classes:** 43 different traffic signs.
* **Image Dimensions:** Resized to 64x64 pixels during preprocessing.
* **Format:** RGB (3-channel) color images.

## Label Mapping
The mapping of class IDs to human-readable names can be found in `data_preprocessing.py` located in this folder.
