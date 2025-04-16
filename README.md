# Hello World Streamlit App

This project demonstrates a simple 'Hello World' application built with Python and Streamlit. The application is implemented in a single file (app.py) and immediately displays the 'Hello World' message upon launch.

## Requirements

- Python 3.x
- Streamlit (install using `pip install streamlit`)

## Installation

1. Ensure that Python 3.x is installed.
2. Install Streamlit by running:
   ```sh
   pip install streamlit
   ```

## Running the Application

To run the application on port 80 with CORS disabled, execute the following command from the project directory (/code):

```sh
streamlit run app.py --server.port 80 --server.enableCORS false
```

This command starts the Streamlit app as a daemon on port 80, with CORS disabled. Once running, you can open your browser and navigate to one of the following URLs to view the app:

- Local URL: [http://localhost:80](http://localhost:80)
- Network URL: (as provided by the system daemon)
- External URL: (as provided by the system daemon)

## Verification

After running the command, the app displays a single message: **Hello World**. This confirms that the application meets the functional requirement.

## Project Structure

- **/code/app.py**: Contains the implementation of the Hello World Streamlit app.
- **/code/.gitignore**: Git ignore file listing files and directories to be excluded from version control.

## Summary

This documentation details the implementation and execution steps for a simple Streamlit Hello World application. It explains the command used for launching the app, as well as the expected output of the app (displaying 'Hello World'). Additionally, it covers the project structure and dependency installation. The application has been verified using automated visual inspection ensuring that the 'Hello World' message is properly rendered.
