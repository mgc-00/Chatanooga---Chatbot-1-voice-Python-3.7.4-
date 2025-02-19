Chatanooga - AI Chatbot

Chatanooga is an AI chatbot designed to interact with users using both speech recognition and text-to-speech capabilities. 
It uses the DialoGPT language model for generating responses and is primarily built in Python 3.7.4. 
This project provides a conversational interface that can be customized and extended based on specific requirements.

Features

    Speech Recognition: Utilizes Google Speech Recognition to convert user speech to text.

    Text-to-Speech: Uses pyttsx3 library to convert text responses back to speech.

    Conversational AI: Based on DialoGPT, enabling dynamic and context-aware responses.

    Custom Training: Includes functionality to fine-tune the chatbot's language model with additional training data.

Requirements

    Python 3.7.4

    PyAudio: Ensure PyAudio-0.2.11-cp37-cp37m-win_amd64.whl is installed in the Python 3.7.4 environment.

1. Installation

    Clone the Repository:
  
	git clone https://github.com/yourusername/chatanooga.git cd 
	
2. Install Dependencies: Install the required Python packages:

	pip install -r requirements.txt

3. Install PyAudio: Ensure PyAudio is installed using the provided .whl file in your Python 3.7.4 folder:

	pip install PyAudio-0.2.11-cp37-cp37m-win_amd64.whl


Usage

1. Run the Chatbot:

	python speekbot.py

2. Interact with Chatanooga:

    Chatanooga listens for your voice commands and responds with synthesized speech.

    Example interactions include asking about the weather, requesting a joke, or general knowledge questions.
	 **** Bot does take a couple of minutes to load before each session****
	 
Customization

    Training Data: Modify new_conversations in speekbot.py to add more examples for training.

    Model Fine-Tuning: Adjust training parameters such as epochs and batch size in the train function.
	
Contributing

Feel free to submit issues, fork the repository, and make pull requests to improve the chatbot. All contributions are welcome!
	
	
