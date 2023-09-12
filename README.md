# Jupyter Notebook of Machine Learning House Price Prediction

This repository is containing Jupyter Notebook file that can make easy to explore and understand what we do and what we process to our datasets. The datasets in this repository is gathered from [Kaggle by Cam Nugent](https://www.kaggle.com/datasets/camnugent/california-housing-prices)

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.
See deployment for notes on how to deploy the project on a live system.

### Prerequisites

Prequisites packages:
* Python 3
* Visual Studio Code with Extensions Installed
  * Python
  * Jupyter Notebook 

### Preparation

1) Create your own Virtual Environment using Python 3 VEnv Module
    ```sh
    python3 -m venv MyWorkspace
    ```

2) Clone this repository as `src` directory under `MyWorkspace` directory that created by Python 3 Virtual Environment
    ```sh
    cd MyWorkspace
    git clone https://github.com/dimaskiddo/jupyter-price-prediction-house.git src
    ```

3) Activate the Virtual Environment and Update PIP
    ```sh
    source bin/activate
    pip install --no-cache-dir --upgrade pip setuptools wheel
    ```

4) Install Dependencies Library for Data Science
    ```sh
    pip install --no-cache-dir numpy pandas scikit-learn matplotlib seaborn
    ```

5) Install Jupyter Notebook Kernel
    ```sh
    pip install --no-cache-dir ipykernel ipython
    ```

## Exploration

1) Open the Visual Studio Code with `MyWorkspace` directory and then select `src/Notebook.ipynb` file

2) At the top of Visual Studio Code select Jupyter Notebook Kernel to Current Python Environment

3) After some auto adjustment made by Visual Studio Code you can start or run Python code from the Jupyter Notebook
