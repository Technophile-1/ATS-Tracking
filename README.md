# ATS-Tracking
The Project describes the project structure for a Streamlit web application  called "Resume ATS Tracker" that analyzes resumes against job descriptions. Here are the steps to create the project folder structure:

1-Create the project folder.
2-Inside the project folder, create the following folders and files:
*)images folder: This folder will store the images used in the user interface.
*).env file: This file will securely store the Google API key.
*)app.py: This file is the primary application file and will contain both the model and Streamlit UI code.
*)requirements.txt: This file will list the libraries required to install for the project to function properly.

Here are the steps to install the required libraries:
1-Open the terminal.
2-Run the following command:
# libraries need to be installed
pip install streamlit
pip install streamlit_extras
pip install google-generativeai
pip install python-dotenv
pip install PyPDF2
pip install Pillow
pip install -r requirements.txt
These command will install all the libraries listed in the requirements.txt file.

Here are the steps to generate a Google API key:

1-Click the provided link to access the following webpage: https://ai.google.dev/gemini-api/docs/api-key
2-After signing in to your account, navigate to the 'Get an API Key' option. Clicking on this option will redirect you to another webpage.
3-Next, click on 'Create API Key' and choose the generative language client as the project. Then, select 'Create API key in existing project'.
4-Copy the newly generated API key as it is required for loading the Gemini Pro pre-trained model.
5-Here are the steps to initialize the Google API key:

1-Create a .env file and define a variable named GOOGLE_API_KEY.
2-Assign the copied Google API key to this variable.

The next steps involve writing code to load the Gemini Pro pre-trained model, implementing functions to get user responses and read PDF content, writing prompts for the Gemini model, integrating the application with a web framework, and finally hosting the application.
