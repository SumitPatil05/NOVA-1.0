# NOVA 1.0 – Voice-Based Personal Assistant

## Overview
NOVA 1.0 is an advanced voice-based personal assistant designed to integrate seamlessly with various use cases, offering intuitive and efficient voice command functionalities. Leveraging Python and key libraries, NOVA 1.0 provides a robust platform for voice interaction and automation.

## Features
- **Voice Interaction**: Communicate with NOVA 1.0 using natural language voice commands.
- **Text-to-Speech**: Convert text responses into speech using `pyttsx3`.
- **Speech Recognition**: Understand and process voice commands using the `speech_recognition` library.
- **Intelligent Responses**: Utilize the WolframAlpha API for answering complex questions and performing calculations.
- **Extensible Design**: Easily extend functionality to support new use cases and integrations.

## Technologies Used
- **Programming Language**: Python
- **Modules**:
  - `pyttsx3` for text-to-speech conversion
  - `speech_recognition` for processing voice commands
- **API**:
  - WolframAlpha for intelligent query responses

## Installation and Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/nova-voice-assistant.git
   cd nova-voice-assistant
   ```

2. **Set Up Virtual Environment**:
   Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows use `venv\Scripts\activate`
   ```

3. **Install Dependencies**:
   Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```

4. **Configure API Key**:
   Obtain an API key from WolframAlpha. Create a `.env` file in the root directory and add your API key:
   ```env
   WOLFRAMALPHA_API_KEY=your_wolframalpha_api_key
   ```

## Usage

1. **Run NOVA 1.0**:
   Start the voice assistant:
   ```bash
   python nova.py
   ```
   NOVA 1.0 will start listening for voice commands.

2. **Give Commands**:
   - **General Queries**: Ask general knowledge questions, and NOVA 1.0 will provide answers using the WolframAlpha API.
   - **Text-to-Speech**: NOVA 1.0 will read out the responses using `pyttsx3`.

## Example Commands
- "What is the capital of France?"
- "Tell me a joke."
- "What is 5 times 7?"

## Extending NOVA 1.0
1. **Add New Commands**:
   Edit `nova.py` to include new voice command functionalities.
   
2. **Integrate New APIs**:
   Add support for additional APIs by importing relevant libraries and updating the command processing logic.

## Contributing
Contributions are welcome! Please follow these steps to contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add YourFeature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements
- [pyttsx3](https://pypi.org/project/pyttsx3/)
- [speech_recognition](https://pypi.org/project/SpeechRecognition/)
- [WolframAlpha](https://www.wolframalpha.com/)

## Contact
For any inquiries or issues, please contact:
* Name: Sumit Patil
* Email: sumitpatilplk920@gmail.com
* GitHub: sumitpatil05


---

Thank you for using NOVA 1.0! Experience the power of voice commands with intelligent automation!
