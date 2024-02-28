Build an Artificial Assistant 

Installation 

For windows users

(run those in command prompt/cmt/terminal) For the robot to listen to our voice/speech pip install speechRecognition

To speak out, or text to speech pip install pyttsx3

For advance control on browser pip install pywhatkit

To get wikipedia data pip install wikipedia

To get funny jokes pip install pyjokes

**Alexa Voice Assistant**
This simple Python script creates a basic voice assistant using the speech_recognition, pyttsx3, pywhatkit, datetime, wikipedia, and pyjokes modules. It allows the user to interact with the voice assistant by providing voice commands.

Features
Play Music on YouTube: Say "play [song name]" to have Alexa play the specified song on YouTube.

Get Current Time: Ask Alexa for the current time, and it will respond with the current time in a 12-hour format.

Get Information: Inquire about a person by saying "who the heck is [person's name]", and Alexa will provide a summary using Wikipedia.

Relationship Status: Ask Alexa if it is single, and it will respond with a humorous answer.

Get Jokes: Request a joke by saying "joke", and Alexa will tell you a joke using the pyjokes module.

Financial Inquiry: Ask Alexa if it has money, and it will respond that it doesn't have money.

Emotional Interaction: Express your feelings to Alexa, like saying "I miss you Alexa", and it will respond accordingly.

Identify Best Friend: Ask Alexa who your best friend is, and it will suggest a name humorously.

How to Use
Install the required modules by running:

Copy code
pip install speech_recognition pyttsx3 pywhatkit wikipedia pyjokes
Run the script.

Begin by saying "Alexa" followed by your command.

Note
Ensure that your system has a working microphone to capture voice commands.

The script uses the Google Speech Recognition API, so an internet connection is required.

Adjust the voices[1].id in the setProperty method to customize the voice of the assistant.

The script runs in an infinite loop, continuously waiting for and processing user commands.

