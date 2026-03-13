# Deep Neural Brain Stroke Detection System (DNBSD)

This project is a web application for detecting brain strokes from CT scan images using a deep learning model.

## Prerequisites

1.  **Python**: Ensure Python is installed (3.7 or higher).
2.  **Model File**: Place your trained model file named `DNBSD.h5` in this folder.

## Installation

1.  Open a terminal (Command Prompt or PowerShell) / VS Code terminal in this folder.
2.  Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## How to Run

1.  Run the application using the following command:
    ```bash
    python app.py
    ```
2.  You will see output indicating the server is running (e.g., `Running on http://127.0.0.1:5001`).

## Usage

1.  Open your web browser and go to:
    [http://127.0.0.1:5001](http://127.0.0.1:5001)
2.  Drag and drop or select a CT scan image.
3.  Click **Analyze Scan** to get the prediction.
