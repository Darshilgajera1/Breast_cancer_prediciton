# Predicting Invasive Ductal Carcinoma (IDC) in Tissue Slices

## Project Overview
This project aims to predict invasive ductal carcinoma (IDC) in breast cancer tissue images using deep learning techniques. IDC is the most common type of breast cancer, and early detection is crucial for effective treatment. The project automates the process of detecting IDC in tissue slices, which is traditionally done by pathologists. By leveraging machine learning, we hope to reduce the manual effort and provide more consistent, faster results, particularly in regions lacking expert pathologists.

## Motivation
Invasive ductal carcinoma accounts for approximately 80% of all breast cancer cases. The traditional process of detecting IDC involves a pathologist analyzing biopsy samples to identify cancerous cells and determine the stage of the disease. This manual process can be time-consuming and subjective, depending on the expertise of the pathologist. With deep learning, we aim to automate the detection and localization of tumor cells in tissue samples, making the diagnosis process more efficient and standardized.

## Project Goal
The goal of this project is to build a deep learning model that can predict the presence of IDC in breast cancer tissue images. We aim to improve detection accuracy and provide a tool that can assist pathologists by automatically identifying cancerous cells in tissue samples.

## Dataset
The dataset consists of tissue slices from breast cancer patients. Each sample contains labeled regions indicating whether the tissue is healthy, contains IDC, or has another subtype of breast cancer.

This project uses a dataset hosted on Kaggle. You can download the dataset manually or programmatically using the Kaggle API.

### Downloading the Dataset Manually
1. Visit the [Kaggle dataset page](https://www.kaggle.com/darshilgajera/brest-cancer-prediction).
2. Log in to your Kaggle account.
3. Click the "Download" button to get the dataset.

### Downloading the Dataset Programmatically
If you prefer to download the dataset using the Kaggle API, follow these steps:

1. Install the Kaggle CLI tool:
   ```bash
   pip install kaggle

2. Use the following command to download the dataset:
    ```bash
    kaggle datasets download -d darshilgajera/brest-cancer-prediction
3. Unzip the dataset:
    ```bash
    unzip brest-cancer-prediction.zip
