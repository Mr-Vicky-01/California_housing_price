# California Housing Price Prediction

![OIP](https://github.com/Mr-Vicky-01/California_housing_price/assets/143078285/b43ca991-4174-4c07-bcb6-160ef50a845b)

## Overview

This project focuses on predicting housing prices in California. The dataset provides information about various features within a block, with the goal of predicting the median house value for households.

## Key Features

1. **Longitude:** A measure of how far west a house is; a higher value is farther west.
2. **Latitude:** A measure of how far north a house is; a higher value is farther north.
3. **Housing Median Age:** Median age of a house within a block; a lower number is a newer building.
4. **Total Rooms:** Total number of rooms within a block.
5. **Total Bedrooms:** Total number of bedrooms within a block.
6. **Population:** Total number of people residing within a block.
7. **Households:** Total number of households, a group of people residing within a home unit, for a block.
8. **Median Income:** Median income for households within a block of houses (measured in tens of thousands of US Dollars).
9. **Median House Value:** Median house value for households within a block (measured in US Dollars).
10. **Ocean Proximity:** Location of the house with respect to the ocean/sea.

The XGBoost model has achieved an accuracy of approximately 84.29% on the test set. This suggests that the model performs reasonably well in making correct predictions. However, it's crucial to consider additional evaluation metrics, such as precision, recall, and F1-score, especially in scenarios with class imbalance or where specific types of errors have varying impacts.

In further analysis, it's recommended to assess the model's performance in the context of the specific problem domain. Exploring additional metrics and potentially visualizing the results can provide a more comprehensive understanding of the model's strengths and weaknesses.

## Getting Started

### Prerequisites

- Python 3.x
- XGBoost
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/Mr-Vicky-01/California_housing_price.git
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

### Usage

1. Navigate to the project directory:

    ```bash
    cd California_housing_price
    ```

2. Run the prediction script:

    ```bash
    python predict_housing_prices.py
    ```

## Acknowledgments

- Special thanks to the contributors and creators of the dataset used for this project.


## License

This project is licensed under the [MIT License](LICENSE).

## Project Link

[California Housing Price Prediction GitHub Repository](https://github.com/Mr-Vicky-01/California_housing_price.git)

![download](https://github.com/Mr-Vicky-01/California_housing_price/assets/143078285/1831f52b-e574-4d20-ad83-0e92e4b6c6c5)
