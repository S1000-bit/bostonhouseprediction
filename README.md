# Housy - House Price Prediction App

Housy is a web application built using Flask for predicting house prices. The application uses a machine learning model trained with scikit-learn to make predictions based on user input.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Running the Application](#running-the-application)
- [Docker](#docker)


## Introduction

Housy is designed to help users predict the price of a house based on various features. It leverages a pre-trained machine learning model to provide accurate predictions.

## Features

- User-friendly web interface for inputting house features
- Predicts house prices using a machine learning model
- Visualizations of data trends

## Installation

### Prerequisites

- Python 3.8.10
- Docker (optional, for containerized deployment)

### Steps

1. Clone the repository:

   ```bash
   git clone https://github.com/your-repository.git
   cd your-repository
2. Create virtual environment:
   
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows use env\Scripts\activate

3. Install the required dependencies:
   
    ```bash
   pip install -r requirements.txt

## Usage

To use the application, ensure you have all dependencies installed and your virtual environment activated.

## Running the Application

  You can run the application using Flask. Ensure you are in the project directory and the virtual environment is activated.
  
        export FLASK_APP=app.py
        flask run

## Docker

1. To run the application using Docker, you need to have Docker installed on your machine.

 Build the Docker image:
  
    docker build -t housy-app 

2. Run the Docker container:

       docker run -d -p 5000:5000 housy-app

