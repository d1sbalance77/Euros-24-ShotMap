# Project Name

## Overview

This project is designed to check all shots which was taken in Euros 2024 . The setup and usage instructions below will guide you through creating a virtual environment, installing necessary dependencies, and running the application.

## Setup Instructions

### 1. Creating a Virtual Environment

To ensure that the project dependencies are isolated, it's recommended to create a virtual environment. You can create a virtual environment by following these steps:

1. **Navigate to your project directory**:

    ```bash
    cd /path/to/your/project
    ```

2. **Create a virtual environment**:

    ```bash
    python -m venv venv
    ```

    This command will create a directory named `venv` in your project folder.

3. **Activate the virtual environment**:

    - On **Windows**:

      ```bash
      venv\Scripts\activate
      ```

    - On **macOS/Linux**:

      ```bash
      source venv/bin/activate
      ```

### 2. Installing Dependencies

Once the virtual environment is activated, you can install all necessary dependencies using the `requirements.txt` file:

1. **Install dependencies**:

    ```bash
    pip install -r requirements.txt
    ```

    This command will read the `requirements.txt` file and install all the listed packages into your virtual environment.

### 3. Running the Application

After installing the dependencies, you can run the application using Streamlit:

1. **Run the Streamlit application**:

    ```bash
    streamlit run main.py
    ```

    This command will start the Streamlit server and open the application in your default web browser.

## Additional Information

- **Deactivating the virtual environment**: When you're done working in your virtual environment, you can deactivate it by simply typing `deactivate` in your terminal.
  
- **Modifying dependencies**: If you need to add more packages, install them with `pip install <package-name>`, and don't forget to update `requirements.txt` with `pip freeze > requirements.txt`.
