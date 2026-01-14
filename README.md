OIBSIP_VoiceAssistant_01

Description:
Python-based voice assistant that can speak, play songs on YouTube, open websites,and convert speech to text.

--------------------------------------------------------------
TABLE OF CONTENTS

- Installation
- How to Use
- Description of Commands
- Tech Used
- Contributions
- Methodology

--------------------------------------------------------------
INSTALLATION

1. Download this repository as a ZIP file or clone it.
2. Extract the folder.
3. Open the folder and locate voice_assistant.py
4. Run the script using Python:

   python voice_assistant.py

Note: Make sure you have installed all required libraries:

   pip install SpeechRecognition pyttsx3

Important: If pyaudio gives errors on Windows, follow PyAudio installation instructions.

--------------------------------------------------------------
HOW TO USE

1. Run the script: python voice_assistant.py
2. The assistant will greet you: "Hello. I am ready."
3. Speak your commands clearly.
4. To stop the assistant, say: Stop, Exit, or Goodbye.

--------------------------------------------------------------
DESCRIPTION OF COMMANDS

Command                       | Function
------------------------------|------------------------------------------
Open Google                   | Opens Google in your default browser
Open YouTube                  | Opens YouTube in your default browser
Play [song name]              | Plays the specified song on YouTube search results
Time / What is the time       | Tells the current time
Stop / Exit / Goodbye         | Stops the voice assistant
Anything else                 | Repeats back what you said

Note: Speak clearly for accurate recognition. If the assistant cannot understand, it will prompt you to try again.

--------------------------------------------------------------
TECH USED

- Language: Python
- Libraries: SpeechRecognition, pyttsx3, datetime, webbrowser

--------------------------------------------------------------
CONTRIBUTIONS

- Follow the CONTRIBUTING.md guidelines to contribute.
- Pull requests are welcome!

--------------------------------------------------------------
METHODOLOGY

Voice Assistant Workflow:

1. Initialization: Load text-to-speech engine (pyttsx3) and greet the user.
2. Listen to Commands: Use SpeechRecognition to capture microphone input.
3. Parse Commands: Detect keywords like play, open, time, stop.
4. Execute Actions:
   - Open websites → webbrowser.open()
   - Play songs → Open YouTube search page for the song
   - Tell time → datetime
   - Repeat speech → Echo user input
5. Stop on Command: If user says stop, exit, or goodbye, assistant exits gracefully.

--------------------------------------------------------------

Author: @Ruchitha

THANK YOU!
