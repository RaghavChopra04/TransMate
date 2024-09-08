TransMate
TransMate is a real-time voice translation application that leverages Google APIs and Python libraries to provide seamless and accurate language translation. With an intuitive Tkinter-based graphical user interface (GUI), TransMate allows users to translate spoken words between various languages quickly and efficiently.

Features
Real-Time Translation: Converts spoken words into text and translates them into the selected target language in real-time.
Multi-Language Support: Supports a wide range of languages for both input and output.
User-Friendly Interface: Simple and easy-to-use GUI built with Tkinter.
Google APIs Integration: Utilizes Google Speech Recognition and Translation APIs for accurate and reliable translations.
Installation
To run TransMate locally, follow these steps:

Clone the Repository ------------------------------>


git clone https://github.com/your-username/TransMate.git
cd TransMate


python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

pip install -r requirements.txt

Configure API Keys:
Obtain API keys for Google Speech Recognition and Translation APIs.
Replace placeholders in config.py with your API keys.

Run the Application:

python app.py

USAGE ----------------------------->
Open the Application:

Launch the application by running LaunchTransMate.py from your terminal or command prompt.

Select Languages:
Choose the source and target languages for translation using the dropdown menus.

Speak or Input Text:
Use the microphone to speak the text you want to translate, or input text directly.

View Translation:
The translated text will be displayed in real-time on the GUI.
Example
Here's a quick example of how the application works:

Select "French" as the target language.
Speak "Hello, how are you?" into the microphone.
The application will display and speak the translated text in the output field.

