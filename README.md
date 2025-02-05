# Home Price Prediction using Linear Regression

## Overview
This project demonstrates a simple linear regression model to predict house prices based on area. The model is built using Python with `pandas`, `numpy`, `matplotlib`, and `scikit-learn`. It trains on a dataset of home prices and then predicts prices for a given set of areas.

## Dataset
### `homeprices.csv`
A CSV file containing historical home prices with two columns:
- `area` (Size of the house in square feet)
- `price` (Price of the house in USD)

### `areas.csv`
A CSV file containing new areas for which we want to predict house prices.
- `area` (Size of the house in square feet)

## Dependencies
Make sure you have the following Python libraries installed:
```bash
pip install pandas numpy matplotlib scikit-learn
```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/home-price-prediction.git
   cd home-price-prediction
   ```
2. Place your dataset files (`homeprices.csv` and `areas.csv`) in the project directory.
3. Run the script:
   ```bash
   python home_price_prediction.py
   ```
4. The script will generate `prediction.csv`, which contains the predicted prices.

## Code Explanation
- **Data Visualization**: The script plots house prices against area to understand the trend.
- **Model Training**: Uses `LinearRegression` from `sklearn` to train on `homeprices.csv`.
- **Predictions**: Predicts house prices for given areas in `areas.csv`.
- **Output**: Saves predictions to `prediction.csv`.

## Example Output
### `prediction.csv`
| area  | prices      |
|-------|------------|
| 1000  | 316404.10  |
| 1500  | 384297.95  |
| 2300  | 492928.08  |
| 3540  | 661304.79  |
| 4120  | 740061.64  |

## License
This project is open-source and available under the MIT License.



