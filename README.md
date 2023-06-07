# Random Forest Regression Weather Prediction Project

This project aims to predict weather patterns using a Random Forest Regression model. The Random Forest algorithm is a powerful machine learning technique that combines multiple decision trees to make accurate predictions.

## Dataset

The project utilizes a weather dataset containing real time weather data containing 3 values [temperature, humidity and pressure]. 
The dataset is sourced using NODEMCU Board which was used to collect real time weather data using DHT11 Temperature and Humidity Sensor and BMP180 Atmospheric Pressure Sensor.

## Project Structure

The project repository is organized as follows:

```
- data/
  - feeds.csv        # The weather dataset used for training and testing
- notebooks/
  - rf.ipynb           # Jupyter Notebook containing the Random Forest Regression model implementation
- README.md                    # This README file providing project information and instructions
```

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/gauravgulia26/weather.ml
   ```

2. Install the required dependencies:
   ```
   Debian/Ubuntu-based distributions:
   sudo apt update
   sudo apt install python3-pip
   pip3 install jupyter
   
   Fedora:   
   sudo dnf install python3-pip
   pip3 install jupyter
   
   OpenSUSE
   sudo zypper install python3-pip
   pip3 install jupyter 
   ```

## Usage
1. Open Terminal and Run:
  ```
  mkdir notebooks
  ```
2. Navigate to the `notebooks` directory:
   ```
   cd notebooks
   ```

3. Open the `rf.ipynb` Jupyter notebook to explore and analyze the weather dataset.

4. Open the `rf.ipynb` Jupyter notebook to train and evaluate the Random Forest Regression model.

5. Customize the model parameters, feature selection, and hyperparameter tuning as per your requirements.

## Results

The trained Random Forest Regression model achieves 99.27% Acuuracy. This indicates its effectiveness in predicting weather patterns based on the given dataset.

## Contributing

Contributions to this project are welcome. If you find any issues or have ideas for improvements, please submit a pull request or open an issue.

## License

This project is OpenSource. Feel free to use and modify the code for your own purposes.

## Contact

If you have any questions or inquiries, please contact gouravgulia.2603@gmail.com.

---
