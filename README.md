
# Text-to-Speech (TTS) Demo

Welcome to the Text-to-Speech (TTS) Demo repository! This project demonstrates how to use OpenAI's TTS service to convert text into speech. You can use this code to generate audio from text conversations, like the one provided in the example.

## Getting Started

This section provides an overview of the project and how to get started using it.

### Prerequisites

To use this TTS demo, you will need the following:
- An API key from OpenAI, which you can obtain from [OpenAI's website](https://openai.com/blog/openai-api).
- Python installed on your computer.

Navigate to the project directory:

sh
Copy code
cd tts-demo
Install the required Python packages:

Usage
This section explains how to use the code to generate audio from text conversations. You'll need to set up your API key and provide a conversation in JSON format.

Set up your API key from OpenAI as described in the Prerequisites section.

Create a conversation JSON file (e.g., conversation.json) with the desired text and speaker information. You can refer to the provided example conversation.

Run the script:
python fivewhys.py

Example Conversation
Here's an example of a conversation in JSON format that you can use as a template:
{
  "conversation": [
    {
      "speaker": "alloy",
      "text": "How are you today?"
    },
    {
      "speaker": "fable",
      "text": "I'm doing well, thanks!"
    },
    {
      "speaker": "alloy",
      "text": "That's nice to hear."
    }
  ]
}

Acknowledgment
This project utilizes the Text-to-Speech (TTS) service provided by OpenAI. We acknowledge and thank OpenAI for their valuable technology and services.

# text-to-speech
