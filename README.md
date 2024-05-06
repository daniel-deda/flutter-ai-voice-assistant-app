# AI Voice Assistant App (Flutter)

Welcome to your new voice assistant!

## Features

This project combines OpenAI's ChatGPT API with their Dall-E API to allow users to
talk to the assistant on the app and interact with ChatGPT and generative AI.  

## How to run the app

- Clone the repository to any folder of your choice
- **cd** into the allen folder
- Run the command **flutter run** and the project will start up
- *Enter 1,2, or 3 into the command line for your choice of browser to run the app on*

## Program Flow

- **1)** You speak into the microphone and the app converts your speech to text
- **2)** The app calls ChatGPT through the API and determines whether you are asking 
for an image or not (whether we will need to use Dall-E or not).
- **3)** Based on the response of that API call (to ChatGPT) that we sent, we send
       another API call to the respective API to handle our request.
- **4)** We display the response from the API call and give the user the answer.

*Note: Please contact me at danieldeda165@gmail.com if you have any issues with the code or running it*
