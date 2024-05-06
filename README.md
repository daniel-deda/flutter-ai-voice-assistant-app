# AI Voice Assistant App (Flutter)

Welcome to your new voice assistant!

## Features

This project combines OpenAI's ChatGPT API with their Dall-E API to allow users to
talk to the assistant on the app and interact with ChatGPT and generative AI.  

## Program Flow

**1)** You speak into the microphone and the app converts your speech to text
**2)** The app calls ChatGPT through the API and determines whether you are asking 
       for an image or not (whether we will need to use Dall-E or not).
**3)** Based on the response of that API call (to ChatGPT) that we sent, we send
       another API call to the respective API to handle our request.
**4)** We display the response from the API call and give the user the answer.
