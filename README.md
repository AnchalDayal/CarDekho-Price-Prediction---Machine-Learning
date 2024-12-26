# Used Car Price Prediction

This project aims to develop a machine-learning model that predicts the selling price of a used car based on its features. The model will help sellers price their cars accurately, enabling quicker sales and optimizing the pricing structure in the used car market. It will also assist buyers in identifying competitively priced vehicles, making the entire market more efficient.

## Problem Statement

The used car market in India is dynamic and constantly changing. Car prices can fluctuate widely depending on several factors such as the make and model of the car, its mileage, condition, and other market conditions. This variability makes it difficult for sellers to accurately price their cars, potentially leading to underpricing or overpricing.

## Dataset

The model will be trained using a dataset containing details of used cars listed on CarDekho.com. The dataset includes the following features:

- `car_name`: Name or title of the car (includes model or variant).
- `brand`: The manufacturer or brand of the car (e.g., Toyota, Honda).
- `model`: Specific model of the car.
- `vehicle_age`: Age of the vehicle in years.
- `km_driven`: Total kilometers driven by the car.
- `seller_type`: Type of seller (e.g., individual or dealer).
- `fuel_type`: Type of fuel used (e.g., petrol, diesel, electric).
- `transmission_type`: Type of transmission (e.g., manual, automatic).
- `mileage`: Fuel efficiency of the car in km/l.
- `engine`: Engine size or capacity in liters.
- `max_power`: Maximum power produced by the engine (in horsepower).
- `seats`: Number of seats in the car.
- `selling_price`: Target variable, representing the price of the car.

You can download the dataset [here](https://drive.google.com/file/d/1WtxKHx5uQoFYmAEKNWs0Jdx4jkS-OXDq/view?usp=sharing).

## Objective

The goal of this project is to build a machine learning model that can predict the price of a used car based on the features listed above. This model will assist in:

- **Accurately pricing cars**: Helping sellers price their cars more competitively and attractively.
- **Making informed buying decisions**: Assisting buyers in evaluating car prices based on historical data.
- **Improving the efficiency of the used car market**: By providing a data-driven, transparent pricing mechanism.

## Approach

### 1. Data Preprocessing
   - Handle missing values (if any).
   - Encode categorical variables such as `brand`, `fuel_type`, `seller_type`.
   - Normalize or standardize numerical features like `vehicle_age`, `km_driven`, `mileage`, etc.

### 2. Feature Engineering
   - Transform or create new features if necessary (e.g., derive `vehicle_age` from the manufacturing year).
   - Extract valuable information from features like `car_name` (e.g., model year, variant).

### 3. Model Selection
   - Experiment with various machine learning models such as:
     - Linear Regression
   - Evaluate models based on performance metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared.

### 4. Model Evaluation and Tuning
   - Split the dataset into training and testing sets.

### 5. Prediction and Deployment
   - Once the model is trained and tuned, it will predict the price of a used car based on input features.
   - The model can be deployed as part of a web application for real-time price prediction.

## Benefits

- **For Sellers**:
  - The model helps sellers set competitive and accurate prices for their cars, increasing the chances of a quick sale.
  
- **For Buyers**:
  - Buyers can find cars that are priced more competitively and make informed purchasing decisions.

- **For the Market**:
  - The model will contribute to the overall efficiency of the used car market by ensuring more transparent and fair pricing.

## How to Use

1. Clone this repository to your local machine.
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
