# Task 1: Advanced BMI Calculator

## Project Overview

The Advanced BMI Calculator is a Python-based application designed to calculate and visualize Body Mass Index (BMI). Developed as part of an internship with **Oasis Infobyte**, this project features a graphical user interface (GUI) built using Tkinter and data management with SQLite3. The application provides users with an intuitive way to monitor their BMI and view trends over time.

## Features

- **User Input Validation**: Ensures that the input values for weight and height are positive and valid.
- **BMI Calculation and Categorization**: Computes BMI and classifies it into categories such as Underweight, Normal Weight, Overweight, and Obesity.
- **Data Storage**: Saves user data including weight, height, BMI, and the date in an SQLite database.
- **Data Visualization**: Uses Matplotlib to display historical BMI trends through graphs.

## Getting Started

### Prerequisites

- Python 3.x
- Tkinter
- SQLite3
- Matplotlib
- Pandas

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/advanced-bmi-calculator.git
    cd advanced-bmi-calculator
    ```

2. Install required libraries:
    ```bash
    pip install matplotlib pandas
    ```

### Usage

1. Run the application:
    ```bash
    python bmi_calculator.py
    ```

2. Enter weight and height values into the respective input fields.
3. Click on "Calculate BMI" to get the BMI result and category.
4. Click on "Show BMI Trend" to visualize the historical BMI data.

### Code Overview

- `bmi_calculator.py`: Contains the main application code including GUI setup, BMI calculation, data storage, and visualization.
- `bmi_data.db`: SQLite database file used to store user data.

## Project Details

- **User Input Validation**: Checks if the height and weight are positive values and handles errors gracefully.
- **BMI Calculation**: Uses the formula `BMI = weight (kg) / (height (m))^2` to compute the BMI.
- **Categorization**: Classifies BMI into Underweight, Normal Weight, Overweight, and Obesity based on predefined ranges.
- **Data Storage**: Utilizes SQLite3 to store and manage BMI records.
- **Data Visualization**: Employs Matplotlib to create graphs of BMI trends over time.


## Acknowledgments

- **Oasis Infobyte**: For providing the opportunity to work on this project.
- **Matplotlib**: For enabling data visualization.
- **SQLite3**: For managing the database.


# Task 2: Advanced Password Generator

An **Advanced Password Generator** developed using Python's Tkinter library. This application allows users to generate secure and customizable passwords with a user-friendly graphical interface. 

## Features

- **Randomization**: Generates secure and unpredictable passwords using cryptographically strong random numbers.
- **User Input Validation**: Ensures that the password meets minimum length requirements (at least 8 characters).
- **Character Set Management**: Customizes the password generation process with options to include or exclude uppercase letters, digits, and special characters.
- **Interactive GUI**: Provides an intuitive and easy-to-use interface.
- **Clipboard Integration**: Allows users to copy the generated password directly to the clipboard.

## Acknowledgements

- **Python Documentation**: For providing comprehensive documentation that guided the development of this project.
- **Tkinter Library**: For offering a powerful and easy-to-use graphical user interface toolkit for Python.
- **Secrets Module**: For enabling cryptographically secure random number generation, which is crucial for creating strong passwords.
- **Oasis Infobyte**: For the opportunity and support during my internship, which allowed me to work on this project and enhance my skills.

Thank you to the open-source community and all contributors who continuously provide resources and support that make projects like this possible.

Feel free to customize the template with your specific repository details, license information, and any additional acknowledgments.


# Task 3: Basic Weather App

Welcome to the Basic Weather App repository! This project is part of my internship with **Oasis Infobyte**. The app provides real-time weather updates for any city using HTML, CSS, and JavaScript.

## Features

- **Real-time Weather Updates**: Fetches and displays current weather conditions for any city.
- **Weather Icons**: Shows weather conditions with corresponding icons.
- **User Input**: Allows users to input the city name and view weather details.

## Technologies Used

- **HTML**: Structure of the web page.
- **CSS**: Styling and layout of the web page.
- **JavaScript**: Fetches weather data from the API and updates the UI dynamically.

## API Integration

The app integrates with the WeatherAPI to fetch weather data. Please ensure you have a valid API key from [WeatherAPI](https://www.weatherapi.com/) to use this app.

## Project Structure

- `index.html`: Main HTML file.
- `styles.css`: CSS file for styling.
- `script.js`: JavaScript file for functionality.

**Thank you for checking out my project!** 🎉
