This Python code creates a chatbot interface using tkinter GUI, 
integrating OpenAI's GPT-3.5 for responses and Bard API for analysis.
It imports tkinter for GUI, OpenAI for chatbot, gTTS for text-to-speech, playsound for audio, speech_recognition for voice input,
and requests for HTTP requests. The GUI comprises a chat log, user input field, and buttons for sending messages and voice input.
Functions handle message sending, voice input, and interaction with APIs for generating and analyzing responses.
Users can input messages via text or voice, and responses are displayed in the GUI chat log. The mainloop keeps the GUI window running and responsive.
................................................................................................................................................................................

I have used my OpenAI api and Google Bard api key as you can see in code.

1)If code runs then it is OK.

2)If not:-

....If error occured due to api keys then it means that api key duration is over. You have to create your 
own openai api key and google bard api key and google bard URL, then use them in code. Simply replace my both api keys and URL with your
api keys and your URL.

....If error occured due to other reason then make sure you have all the necessary dependencies and libraries installed.

tkinter: For GUI development

openai: For interaction with the OpenAI GPT-3.5 model

gTTS: For converting text to speech

playsound: For playing audio

speech_recognition: For voice input

requests: For making HTTP requests
