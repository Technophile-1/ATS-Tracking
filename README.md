# Project Title

A brief description of your project goes here. Explain what the project does and its purpose.

## Project Structure

```
project-folder
├── images          # Folder for storing images used in the UI
├── .env            # File for securely storing the Google API key
├── app.py          # Main application file containing model and Streamlit UI code
├── requirements.txt # Lists libraries and dependencies for the project
└── README.md       # Documentation for the project
```

## Setup Instructions

1. Clone the repository:
   ```
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```
   cd project-folder
   ```
3. Create a virtual environment (optional but recommended):
   ```
   python -m venv venv
   ```
4. Activate the virtual environment:
   - On Windows:
     ```
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```
     source venv/bin/activate
     ```
5. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

## Usage

1. Ensure that your Google API key is stored in the `.env` file.
2. Run the application:
   ```
   python app.py
   ```
3. Open your web browser and navigate to `http://localhost:8501` to access the application.

## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.