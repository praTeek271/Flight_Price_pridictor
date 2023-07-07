# Flight Fare System

This is a Flight Fare System implemented using Python and machine learning techniques, specifically the Random Forest algorithm. The system is built with Flask, a Python web framework, to provide a user-friendly interface for predicting flight fares based on various input parameters.

## Features

- Predicts flight fares based on input parameters such as departure time, arrival time, airline, source, and destination.
- Utilizes a Random Forest machine learning model trained on historical flight data.
- Provides a web-based interface for users to input their flight details and receive fare predictions.
- Implements cross-origin resource sharing (CORS) to handle requests from different domains.

## Prerequisites

Make sure you have the following dependencies installed:

- Python 3.x
- Flask
- scikit-learn
- pandas

## Installation

1. Clone this repository to your local machine or download the source code as a ZIP file.
2. Open a terminal or command prompt and navigate to the project directory.
3. Create a virtual environment (optional but recommended).
4. Install the required dependencies by running the following command:

```
pip install -r requirements.txt
```

## Usage

1. Ensure that you have the trained machine learning model file, "flight_rf.pkl," available in the project directory. This file contains the serialized Random Forest model that will be used for flight fare predictions. If you don't have this file, please obtain it from the appropriate source.
2. In the terminal or command prompt, navigate to the project directory.
3. Run the following command to start the Flask development server:

```
python app.py
```

4. Once the server is running, open a web browser and go to `http://localhost:5000` to access the Flight Fare System interface.
5. Enter the required flight details such as departure time, arrival time, airline, source, destination, and the number of stops.
6. Click on the "Predict" button to receive a fare prediction based on the provided input parameters.

## Customization

If you want to customize or enhance the system, you can explore the following areas:

- Improve the machine learning model: You can try different algorithms, feature engineering techniques, or hyperparameter tuning to improve the prediction accuracy.
- Enhance the user interface: Modify the HTML templates in the `templates` folder to improve the look and feel of the application.
- Extend functionality: You can add additional features such as displaying historical fare trends, integrating with payment gateways, or incorporating user authentication.
- Handle edge cases: Implement error handling and validation to handle unexpected or invalid input from users.

## Contributing

Contributions to this project are welcome. If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request on GitHub.

## License

This project is licensed under the MIT License. Feel free to use and modify it for your own purposes.

## Acknowledgments

Special thanks to the developers and contributors of Flask, scikit-learn, and pandas for providing the tools and libraries used in this project.

## Disclaimer

Please note that the flight fare predictions provided by this system are for demonstration purposes only and may not reflect actual flight prices. The accuracy of the predictions depends on the quality and relevance of the training data used for the machine learning model. Always refer to official flight booking platforms or consult with airlines for accurate and up-to-date fare information.
