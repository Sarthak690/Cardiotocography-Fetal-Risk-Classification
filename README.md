# Cardiotocography Fetal Risk Classification

This repository contains a Python machine learning project for Cardiotocography (CTG) fetal risk classification. The dataset used in this project is obtained from Kaggle.

## Dataset

The dataset used for this project is sourced from Kaggle and contains various features extracted from CTG exams, including fetal heart rate (FHR) patterns and uterine contractions. The target variable is the fetal risk classification.

Dataset source: [Kaggle - Cardiotocography](https://www.kaggle.com/datasets/akshat0007/fetalhr)

## Project Overview

The main objective of this project is to develop a machine learning model to classify the fetal risk based on the CTG exam features. The project includes various ensemble techniques, such as boosting and bagging, to enhance the model's performance and robustness.

## Installation

To run the code in this repository, please follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/Sarthak690/Cardiotocography-Fetal-Risk-Classification.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Cardiotocography-Fetal-Risk-Classification
   ```

3. Install Jupyter Notebook if you haven't already:

   ```bash
   pip install notebook
   ```

## Usage

1. Ensure you have the dataset file (`CTG.csv`) in the project directory.

2. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

3. Open the `main.ipynb` notebook file in Jupyter Notebook.

4. Follow the instructions and run the code cells in the notebook to preprocess the data, train the machine learning models using ensemble techniques, and evaluate the models on test data.

5. The trained models will be saved in the `models` directory, and the evaluation results will be displayed in the notebook.

## Project Structure

The project structure is organized as follows:

- `data/`: Directory to store the dataset file (`CTG.csv`).
- `models/`: Directory to save the trained machine learning models.
- `main.ipynb`: Jupyter Notebook file containing the main code for the project.
- `README.md`: Project overview and instructions (you are here).
- `requirements.txt`: File listing the required Python dependencies.

## Contributing

Contributions to this project are welcome. If you have any suggestions, bug reports, or enhancements, please open an issue or submit a pull request.
