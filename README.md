# Linear Regression Projects

This repository contains two projects utilizing linear regression for predictive analysis: the Bike Rental Prediction System and the Medical Insurance Amount Prediction System. Both projects are built using Python and Streamlit, and they share common requirements.

## Projects

### 1. Bike Rental Prediction System

This project predicts the total number of bike rentals based on various input features using a pre-trained linear regression model.

### 2. Medical Insurance Amount Prediction System

This project predicts the medical insurance amount a person will be charged based on their attributes using a pre-trained linear regression model.

## Installation

1. **Clone the repository**:
    ```sh
    git clone https://github.com/yourusername/linear-regression-projects.git
    cd linear-regression-projects
    ```

2. **Install the required dependencies**:
    ```sh
    pip install -r requirements.txt
    ```

3. **Run the Streamlit app for Bike Rental Prediction**:
    ```sh
    streamlit run bike_rental_app.py
    ```

4. **Run the Streamlit app for Medical Insurance Amount Prediction**:
    ```sh
    streamlit run insurance_app.py
    ```

## Usage

### Bike Rental Prediction System

- Once the Streamlit app is running, you will see a web interface.
- Use the provided input fields to enter the required features.
- Click the "Submit" button to get the prediction for the total number of bike rentals.

### Medical Insurance Amount Prediction System

- Once the Streamlit app is running, you will see a web interface.
- Use the provided input fields to enter the required features.
- Click the "Submit" button to get the prediction for the medical insurance amount.

## Models

Both projects use pre-trained linear regression models saved as pickle files. The model files (`bike_rental_model.pkl` and `insurance_model.pkl`) are included in the repository.

## Files

- `bike_rental_app.py`: The Streamlit application script for the Bike Rental Prediction System.
- `insurance_app.py`: The Streamlit application script for the Medical Insurance Amount Prediction System.
- `requirements.txt`: List of required Python packages.
- `bike_rental_model.pkl`: The pre-trained model file for the Bike Rental Prediction System.
- `insurance_model.pkl`: The pre-trained model file for the Medical Insurance Amount Prediction System.

## Contributing

Feel free to contribute to this project by submitting issues or pull requests. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- These projects were developed using [Streamlit](https://www.streamlit.io/).
- Special thanks to the authors of the datasets and tools used in these projects.


