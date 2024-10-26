# talking-dictionary

**Overview**
The Talking Dictionary is a user-friendly application built using Python and Tkinter. It allows users to enter a word and retrieve its meaning while also providing audio support for the word and its meaning. The application leverages a JSON file to store word definitions and uses pyttsx3 for text-to-speech functionality.

**Features**
Word Lookup: Enter a word to find its meaning.
Audio Support: Pronounce the entered word and read out the meaning.
Suggestions: Provides suggestions for closely matched words if the entered word does not exist.
Clear and Exit Options: Easily clear input and meanings or exit the application.

**Requirements**
Python 3.x
Tkinter (usually included with standard Python installations)
pyttsx3 library for text-to-speech functionality
json for data handling

**Installation**
Ensure you have Python installed on your system.
Install the pyttsx3 library if not already installed:
pip install pyttsx3
Download or clone the repository containing the Talking Dictionary code.
Place your word definition JSON file (e.g., data (1).json) in the same directory as the code.
Update the image file paths in the code to match your local setup, or add the images to the project directory.
**Run the application using:**

python talking_dictionary.py

**How to Use**
1. Launch the application. You will see a text entry box and buttons for searching and audio functions.
2. Enter a word in the provided text field.
3. Click the search button (or press Enter) to retrieve the meaning.
4. Use the microphone button to hear the pronunciation of the word.
5. The meaning will be displayed below. Click the audio button to hear the meaning read aloud.
6. You can clear the input and output fields using the clear button or exit the application using the exit button.

**Data Format**
The application requires a JSON file for storing word meanings. The structure of the JSON file should be:
{
    "word1": [ "definition1"]
    "word2": ["definition1", "definition2"]
}


**Acknowledgments**
Thanks to the Python and Tkinter communities for their resources and documentation.
Special thanks to the pyttsx3 library for enabling text-to-speech features.



