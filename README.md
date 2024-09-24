Speech to YouTube Search Application
This application allows users to record their voice, convert the speech to text, and then perform a YouTube search based on the recognized speech. Built with Python's Tkinter library, SoundDevice, and SpeechRecognition packages, it provides a simple and interactive interface.

Features
Record audio for 5 seconds using your microphone.
Convert the recorded speech into text.
Automatically search YouTube based on the recognized text.
User-friendly interface with animated listening status.
Prerequisites
To run this application, you need to have the following installed on your system:

Python 3.x
Pip (Python package installer)
Installation
Clone or Download the Repository:

You can clone the repository using Git or download the ZIP file.

bash
Copy code
git clone <repository-url>
Navigate to the Project Directory:

Open your terminal or command prompt and navigate to the directory where the project files are located.

bash
Copy code
cd <project-directory>
Install Required Packages:

Use pip to install the required libraries. You can run the following command in your terminal:

bash
Copy code
pip install sounddevice numpy scipy SpeechRecognition
If you are using Windows, you may also need to install the PyAudio library:

bash
Copy code
pip install pyaudio
Usage
Run the Application:

Execute the following command in your terminal or command prompt to start the application:

bash
Copy code
python <script_name>.py
Replace <script_name> with the name of your Python file (e.g., speech_to_youtube.py).

Recording Speech:

Click on the heart-shaped button labeled "💖 Record Speech 💖" to start recording.
Speak clearly into your microphone for about 5 seconds.
Search YouTube:

After recording, the application will convert your speech to text.
It will then automatically open your web browser and perform a YouTube search based on the recognized speech.
Additional Notes
Ensure your microphone is set up and working properly.
You may need to allow access to your microphone depending on your operating system's settings.
If you encounter any issues with speech recognition, try adjusting your microphone settings or speaking clearly.
