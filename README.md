# Rust_Vulnerabile_code_detection_using_CodeBert

This project applies machine learning techniques to detect vulnerabilities in Rust code using an embedded feature representation. The notebook contains data preparation, model training, and evaluation steps.

#Requirements
To run the notebook, make sure you have the following installed:

Python 3.8+

Jupyter Notebook or Google Colab

Required libraries:

bash
Copy
Edit
pip install numpy pandas scikit-learn matplotlib
How to Run
Open the notebook file RUST_FINETO.ipynb using Jupyter Notebook or upload it to Google Colab.

Run the cells sequentially to:

Load and process the dataset.

Train and evaluate a machine learning model (e.g., Random Forest).

View metrics like precision, recall, F1-score, and confusion matrix.

# Dataset
The dataset contains 162 Rust code samples which will be labeled as vulnerable(0) or non-vulnerable(1). Each code snippet is embedded using a pre-trained model with 768-dimensional feature vectors.

# Output
The model outputs classification metrics and a confusion matrix to evaluate performance on detecting vulnerabilities.
