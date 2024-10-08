# Smart Transaction Project

## Overview

The **Smart Transaction Project** is a blockchain-based application designed to facilitate secure and transparent transactions. This project implements a simple interface to manage transactions and track investments, providing both backend services and frontend interaction. The application is powered by Python, Flask, and an SQLite database.

## Features

- **User-friendly interface**: Built using HTML templates, the front-end is simple and easy to navigate.
- **Database integration**: Tracks transactions and investments using SQLite.
- **Modular design**: Separate modules for database operations, forms, and models.
- **Smart contract interaction**: Supports blockchain-based transaction logging (assumed based on context).

## Prerequisites

To run the project, ensure you have the following installed:

- Python 3.x
- Flask
- SQLite

## Project Structure

- `app.py`: The main application file to start the Flask server.
- `db_operations.py`: Manages the operations and interactions with the SQLite database.
- `forms.py`: Contains the forms required for user interactions.
- `models.py`: Defines the database models for transactions and investments.
- `setup_db.py`: A script to initialize the database schema.
- `investments.db`: The SQLite database containing transaction records.
- `templates/`: Holds the HTML files for the front-end interface.

## Installation

1. Clone this repository:
   ```bash
   git clone <repository-url>
Install the required Python packages:

bash
pip install -r requirements.txt
Set up the database:

bash 
python setup_db.py
Run the Flask application:

bash 
python app.py

Usage
Navigate to the main page in your browser (usually http://127.0.0.1:5000/).
Interact with the forms to perform and track transactions.
View transaction histories in the application dashboard.


Future Enhancements
Integration with blockchain networks for actual smart contract execution.
Additional security measures for transaction validation.
Improved front-end with more user-friendly UI.


Contributing
Feel free to submit issues or pull requests for any bugs or new features. Contributions are welcome!

License
This project is open-source and available under the MIT License.