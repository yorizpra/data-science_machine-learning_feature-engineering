# Feature Engineering with Synthetic Data

This project demonstrates feature engineering techniques using a synthetic dataset generated with Scikit-learn. The notebook covers data generation, preprocessing, feature selection, handling imbalanced data, and scaling.

## Table of Contents

- Installation
- Usage
- [Project Structure](#project-structure)
- [Feature Engineering Steps](#feature-engineering-steps)
- License

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yorizpra/feature-engineering.git
    cd feature-engineering
    ```

2. Create a virtual environment and activate it:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Open the Jupyter Notebook:
    ```sh
    jupyter notebook
    ```

2. Navigate to `feature_engineering.ipynb` and run the cells to see the feature engineering process.

## Project Structure
- `data/`: Directory to store any data files.
- `feature_engineering.ipynb`: Jupyter Notebook containing the feature engineering process.
- `README.md`: Project documentation.
- `requirements.txt`: List of required Python packages.
- `venv/`: Virtual environment directory.

## Feature Engineering Steps

1. **Data Generation**: Generate synthetic data using `make_classification` from Scikit-learn.
2. **Data Preparation**: Convert the generated data into a Pandas DataFrame and simulate categorical features.
3. **Feature Selection**: Use Random Forest to select important features.
4. **Handling Imbalanced Data**: Apply SMOTE (Synthetic Minority Oversampling Technique) to balance the dataset.
5. **Scaling**: Standardize the features to have a similar scale.
