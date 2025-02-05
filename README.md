# Traffic Flow Prediction

Traffic Flow Prediction is a time-series forecasting project designed to predict traffic congestion using historical data. The project utilizes the SARIMA (Seasonal AutoRegressive Integrated Moving Average) model to analyze traffic patterns and forecast future conditions.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model](#model)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features
- Time-series prediction of traffic flow
- Utilizes SARIMA model for forecasting
- Data preprocessing and feature engineering
- Model evaluation with performance metrics

## Installation
To install and run the project locally, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/Magnus0969/Traffic-Flow-Prediction.git
   cd Traffic-Flow-Prediction
   ```

2. Create a virtual environment (optional but recommended):
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage
Run the following command to train the model:
```sh
python train.py
```

To make predictions using a trained model:
```sh
python predict.py --input data/sample_input.csv
```

## Dataset
The dataset consists of time-series traffic data, including:
- Timestamps
- Traffic volume
- Weather conditions
- Road conditions

## Model
The project primarily uses the SARIMA model for traffic prediction. The methodology includes:
- Identifying seasonality and trends in traffic data
- Differencing and transformation to achieve stationarity
- Parameter tuning for optimal SARIMA configuration

## Results
Model performance is evaluated using metrics such as:
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R-squared score (R²)

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature-branch`)
5. Open a Pull Request

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For any inquiries, reach out via:
- Email: kmagadi09@gmail.com

