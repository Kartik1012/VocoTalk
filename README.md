# VocoTalk
voice conversational bot
The conversational pipeline model integrates Deepgram Nova2 and GPT-4o Mini to provide a seamless speech-to-speech interaction. It uses Deepgram's advanced speech-to-text (STT) capabilities to transcribe spoken input, which is then processed by GPT-4o Mini to generate relevant text responses. These text responses are converted back into speech using Deepgram's text-to-speech technology. The conversation is initiated by pressing a 'start call' button and continues until an 'end call' button is pressed. To maintain context throughout the interaction, the entire conversation history is continuously passed to the LLM, ensuring coherent and contextually aware responses at each stage of the dialogue.
