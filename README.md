
# Healthcare Translation App Using Generative AI
Healthcare Translation App for real-time voice-to-text and translation app

## Overview

This is a prototype web application designed for real-time transcription and translation, specifically tailored for healthcare settings. The application leverages the Web Speech API for speech recognition and text-to-speech functionalities, and the OpenAI API for translation.

This project was built as a pre-interview assignment with a 48-hour deadline.

## Project Structure

- **index.html**: The main HTML file containing the structure and layout of the application.
- **style.css**: Inline CSS within the HTML file for basic styling.
- **script.js**: JavaScript code embedded within the HTML file to handle speech recognition, translation, and text-to-speech functionalities.

## Features

- **Real-Time Transcription**: Uses the Web Speech API to transcribe spoken language in real-time.
- **Translation**: Translates the transcribed text into a selected language using the OpenAI API.
- **Text-to-Speech**: Reads out the translated text using the Web Speech API.

## Usage

- **Start Listening**: Click the "Start Listening" button to begin speech recognition.
- **Stop Listening**: Click the "Stop Listening" button to stop speech recognition.
- **Speak Translated Text**: Click the "Speak Translated Text" button to read out the translated text.

## Future Improvements
- Secure backend for API calls
- Add more languages and medical domain-specific tuning
- Automated language detection
- Save transcripts securely for record-keeping

## API Key

The application requires an OpenAI API key to function. Ensure you have your API key and replace the placeholder in the script with your actual key but this is a prototype so i had actually put my key.

## Browser Compatibility

The application uses the Web Speech API, which may not be supported in all browsers. For the best experience, use the latest version of Chrome.

## Notes

This prototype is for demonstration purposes and may require further development for production use.


