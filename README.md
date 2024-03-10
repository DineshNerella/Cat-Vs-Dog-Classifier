# Cat vs Dog Classifier

This repository contains code for training a cat vs dog classifier using deep learning techniques in a Jupyter Notebook. The dataset is directly imported from Kaggle to Google Colab for seamless integration and experimentation.

## Overview

In this project, we aim to build a deep learning model that can accurately classify whether an image contains a cat or a dog. We'll use convolutional neural networks (CNNs) for image classification and train the model on a dataset containing images of cats and dogs.

## Usage Instructions

To replicate this project in Google Colab, follow these steps:

1. **Install Dependencies**
2. **Authenticate Kaggle API**
   - Authenticate the Kaggle API by uploading your Kaggle API token. Follow these steps:
     - Go to your Kaggle account settings page.
     - Scroll down to the API section and click on "Create New API Token".
     - Save the `kaggle.json` file to your local machine.
     - Upload the `kaggle.json` file to your Google Colab environment using the following code:
       ```
       from google.colab import files
       files.upload()
       ```

3. **Download the Dataset**
   - Use the Kaggle API to download the dataset directly to your Colab environment. Execute the following command:
     ```
        !kaggle datasets download -d salader/dogs-vs-cats
     ```
     
4. **Extract Dataset Files**
5. **Access Dataset Files**
6. **Run the Jupyter Notebook**:
   - Upload the provided Jupyter Notebook (`cat_vs_dog_classifier.ipynb`) to your Google Colab environment.
   - Open and run the notebook cells to train and evaluate the classifier.

