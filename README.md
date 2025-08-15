### Emotion Extraction and Classification from Twitter Text

This Jupyter Notebook, `Emotion_Extraction_and_Classification_from_Twitter_Text.ipynb`, presents a project focused on detecting and classifying human emotions from text, specifically Twitter text. The notebook is a research project for a course and demonstrates the use of a deep learning approach for textual analysis.

#### Project Overview

The main objective is to identify and classify emotional states expressed in text, such as *anger*, *surprise*, *joy*, *fear*, *sadness*, and *love*. The notebook is structured to perform this task, likely including data loading, text preprocessing, model building, and evaluation. It is designed to be run in a Google Colab environment, and it connects to Google Drive to access the necessary data.

#### Dependencies

The notebook uses a variety of Python libraries for data handling, deep learning, and evaluation. To run this script, you need to install the following:

* `pandas`
* `numpy`
* `re`
* `torch`
* `sklearn` (specifically `sklearn.metrics`)
* `tensorflow` (specifically `tensorflow.keras.preprocessing.text` and `tensorflow.keras.preprocessing.sequence`)
* `matplotlib`

#### How to Use

1.  **Environment:** This notebook is designed for a Google Colab environment. Open it in Google Colab to get started.
2.  **Google Drive:** Since the notebook includes code to mount Google Drive, ensure your dataset is stored there in a path matching `"/content/drive/MyDrive/CSE/4.2/CSE4238 - Soft Computing Lab/Project - Emotion Detection from Twitter Text/"`.
3.  **Run Cells:** Execute the cells sequentially. The code will handle importing the necessary libraries, loading the data, and performing the emotion classification task.
