# Nova - Voice-Based Virtual Assistant

Nova is a voice-based virtual assistant that aims to assist you in various aspects of your day-to-day life. With Nova, you can interact with a virtual assistant using voice commands, ask questions, and get intelligent responses. Whether you need help with tasks, want to engage in conversations, or simply have a friendly voice to assist you, Nova is here for you.

## Features
- **Voice Recognition**: Nova utilizes the SpeechRecognition library to listen and recognize user voice commands.
- **Text-to-Speech**: The pyttsx3 library is used to convert text into speech, allowing Nova to respond audibly to user queries.
- **ChatGPT Integration**: Nova leverages the OpenAI ChatGPT API to generate intelligent responses and engage in conversations.
- **User Interaction**: Users can interact with Nova by speaking commands, asking questions, or engaging in conversations.
- **Continuous Conversation**: Nova maintains a continuous conversation flow, allowing users to have back-and-forth interactions.
- **Extensibility**: Nova can be extended with additional functionalities and capabilities to suit your specific needs.

## Getting Started
To use Nova, follow these steps:

1. Clone the repository to your local machine.
2. Install the required dependencies by running the following command:
   ````
   pip install -r requirements.txt
   ```
3. Set up your API credentials:
   - Obtain an API key from the OpenAI ChatGPT API.
   - Create a `.env` file in the project directory and add the following line:
     ```
     OPENAI_API_KEY=<your-api-key>
     ```
4. Run the `nova.py` script:
   ````
   python nova.py
   ```
5. Start interacting with Nova by speaking commands, asking questions, or engaging in conversations.

## Example Usage
Once you have set up and launched Nova, you can start interacting with it. Here's an example conversation:

```
User: You are Nova, you are here to assist me in various aspects of my day-to-day life.
Nova: Hello! I'm Nova, your virtual assistant. How can I assist you today?

User: What's the weather like today?
Nova: I'm sorry, I don't have access to real-time weather information. However, I can help you with a wide range of other tasks or answer questions you may have.

User: Can you tell me a joke?
Nova: Sure! Here's a joke for you: Why don't scientists trust atoms? Because they make up everything!

User: Thank you.
Nova: You're welcome! If you have any more questions or need further assistance, feel free to ask.
```

Feel free to engage in conversations, ask questions, or give commands to Nova and explore its capabilities.

## Contributing
Contributions to Nova are welcome! If you have any ideas, bug reports, or feature requests, please open an issue on the GitHub repository. You can also submit pull requests with your proposed changes.

## License
This project is licensed under the [MIT License](LICENSE).

## Disclaimer
Nova is an open-source project developed by [Yasamin-Alemzadeh]. It is provided as-is and without any warranty. Use Nova at your own risk.
