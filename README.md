# SQL to Text App with Streamlit and SQLite

This is a Streamlit web application that converts English questions into SQL queries and retrieves data from an SQLite database named "STUDENT". The application utilizes Google Gemini Pro for natural language understanding and SQL generation.

## Features

- **Gemini Pro Integration**: Leverages the power of Google Gemini Pro to generate SQL queries from English questions.

- **SQLite Database**: Connects to an SQLite database named "STUDENT" with columns - NAME, CLASS, SECTION.

- **Streamlit Interface**: Provides a user-friendly interface for entering questions and retrieving SQL query responses.

## Prerequisites

1. Obtain a Google API key for Gemini Pro from the [Google Cloud Console](https://console.cloud.google.com/).

2. Install the required Python packages:

   ```bash
   pip install -r requirements.txt

## Create a .env file and add your Google API key:

GOOGLE_API_KEY=your_google_api_key

## Setup

Create the SQLite database file named student.db with the necessary schema.
Run the Streamlit app:
streamlit run app.py
Access the app in your web browser by navigating to the provided URL.

## Usage

Enter an English question in the input field.
Click the "Ask the question" button to generate the corresponding SQL query using Gemini Pro.
View the SQL query response retrieved from the "STUDENT" database.

