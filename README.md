# House Price Prediction

This project implements a linear regression model to predict house prices based on square footage, number of bedrooms, and number of bathrooms.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The goal of this project is to predict house prices using a linear regression model. The model uses three main features:
- Square footage of the house (`GrLivArea`)
- Number of bedrooms (`BedroomAbvGr`)
- Number of bathrooms (`TotalBath`, which is the sum of full bathrooms and half bathrooms where half bathrooms are counted as 0.5)

## Dataset

The dataset includes two CSV files:
- `train.csv`: Contains the training data with house features and prices.
- `test.csv`: Contains the test data with house features without prices.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/house-price-prediction.git
    cd house-price-prediction
    ```

2. Create and activate a virtual environment (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Ensure the dataset files (`train.csv` and `test.csv`) are in the project directory.

2. Run the Jupyter Notebook to train the model and make predictions:
    ```bash
    jupyter notebook
    ```

3. Open `house_price_prediction.ipynb` and run all the cells to train the model and generate predictions.

## Results

The model's performance is evaluated using Mean Squared Error (MSE) on the validation set. The predicted prices for the test dataset are saved in `submission.csv`.

## Contributing

Contributions are welcome! Please open an issue to discuss what you would like to change.

1. Fork the repository.
2. Create a new branch:
    ```bash
    git checkout -b feature-branch
    ```
3. Make your changes and commit:
    ```bash
    git commit -m "Description of changes"
    ```
4. Push to the branch:
    ```bash
    git push origin feature-branch
    ```
5. Open a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
