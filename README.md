# Text-To-Speech

Project Summary: Speech Synthesis App
This project is a web-based speech synthesis application that converts text input into spoken words using the browser's speech synthesis API. The application allows users to select different voices and listen to the spoken output of their text.

Key Features:
Voice Selection: Users can choose from different available voices provided by the browser. The app dynamically populates the voice options in a dropdown menu based on the voices available on the user's system.
Text-to-Speech: When the user clicks the "Speak" button, the text entered in a textarea is converted into speech.
Dynamic Voice Loading: The available voices are loaded and updated automatically when the browser's speech synthesis voices change.
How It Works:
Loading Voices: When the speech synthesis voices are loaded or changed, the app populates a dropdown menu with available voices.
Text-to-Speech Conversion: Upon clicking the button, the app retrieves the text from the textarea and converts it into speech using the selected voice.
This application demonstrates how to use the Web Speech API to create a text-to-speech feature with customizable voice options, making it a useful tool for accessibility and language learning applications.
