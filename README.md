
# VocaScribe

**VocaScribe** is a voice-to-text and text summarization tool. It takes input through voice, converts it into text, and then summarizes the content for easier understanding. The project aims to integrate speech recognition and natural language processing (NLP) techniques to provide an efficient voice-to-text system with automatic summarization.

## Features
- **Voice Input**: Capture speech through a microphone.
- **Speech-to-Text Conversion**: Convert the speech into written text using state-of-the-art speech recognition models.
- **Text Summarization**: Automatically summarize the transcribed text to highlight key points.
- **Easy Integration**: Can be integrated into web applications or used as a standalone tool.

## Installation

To get started with **VocaScribe**, clone the repository to your local machine and install the necessary dependencies:

1. Clone the repository:
   ```bash
   git clone https://github.com/jani1217/VocaScribe.git
   cd VocaScribe
   ```
2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Capture Audio and Convert to Text**:
   - The project captures voice input through the microphone and transcribes it into text.
   - You can run the script to test the voice-to-text functionality.

2. **Summarize Text**:
   - After converting the voice input to text, the tool summarizes the text using a natural language processing model.

3. **Running the Project**:
   - You can run the script directly in your terminal to use the voice-to-text and summarization functionality.

## Requirements
- Python 3.x
- `speechrecognition` library for speech-to-text conversion
- `transformers` for text summarization
- `pyaudio` for audio input (may require additional setup depending on OS)

## Contributing

Feel free to fork this project, open issues, and submit pull requests. Contributions are welcome!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements
- SpeechRecognition library for speech-to-text conversion.
- Hugging Face Transformers for text summarization.
- PyAudio for audio input.
```

