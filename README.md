# Flight Fare Price Prediction Web Application

This repository contains a Flight Fare Price Prediction web application that uses a Random Forest Regression model to predict flight fares. The model achieves an R-squared score of 0.84 and incorporates feature engineering and exploratory data analysis (EDA) techniques. The application is built using Flask framework to provide a user-friendly interface for users to input flight details and obtain fare predictions.

## Table of Contents

- [Project Overview](#project-overview)
- [Model Performance](#model-performance)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

This project focuses on predicting flight fares using a Random Forest Regression model. It involves several key steps:

1. **Data Collection**: Gather flight data including features such as departure and arrival locations, departure time, airlines, etc.

2. **Exploratory Data Analysis (EDA)**: Analyze the collected data to understand patterns, correlations, and potential outliers. EDA helps in identifying useful features for the prediction model and provides insights into the dataset.

3. **Feature Engineering**: Enhance the dataset by creating new features, handling missing values, and converting categorical variables into numerical representations.

4. **Model Development**: Build a Random Forest Regression model to predict flight fares based on the engineered features. Tune hyperparameters to achieve optimal performance.

5. **Web Application**: Develop a web application using Flask that allows users to input flight details and obtain fare predictions from the trained model.

## Model Performance

The developed Random Forest Regression model achieves an R-squared score of 0.84 on the test dataset, indicating strong predictive performance.

## Features

- **Random Forest Regression**: The core of the prediction model, utilizing an ensemble of decision trees to make accurate fare predictions.
  
- **Feature Engineering**: Engineered features from raw data to enhance predictive power, including one-hot encoding for categorical variables and handling missing values.
  
- **Exploratory Data Analysis (EDA)**: Thoroughly analyzed the dataset through visualizations and statistical summaries to uncover insights and correlations.

- **Web Application**: The Flask-based web application offers a user-friendly interface for users to input flight details and receive fare predictions.

## Installation

To run the web application locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/flight-fare-prediction.git
   ```

2. Navigate to the project directory:

   ```bash
   cd flight-fare-prediction
   ```

3. Install the required packages using `pip`:

   ```bash
   pip install -r requirements.txt
   ```

4. Run the Flask application:

   ```bash
   python app.py
   ```

5. Access the application in your web browser by navigating to `http://localhost:5000`.

## Usage

1. Input flight details including departure and arrival locations, departure time, airlines, etc.

2. Click the "Predict" button to obtain a fare prediction based on the trained Random Forest Regression model.

3. The predicted fare will be displayed on the web page.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.

2. Create a new branch for your feature or bug fix:

   ```bash
   git checkout -b feature/your-feature-name
   ```

3. Make your changes and commit them:

   ```bash
   git commit -m "Add your commit message here"
   ```

4. Push your changes to your fork:

   ```bash
   git push origin feature/your-feature-name
   ```

5. Create a pull request detailing your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to customize this README according to your project's specific details and structure. Good luck with your Flight Fare Price Prediction web application!
