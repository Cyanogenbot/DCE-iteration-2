# DCE-iteration-2

A simple chatbot example for TU/e Industrial Design's Master course Designing Conversational Experiences. The example builds on an earlier iteration, and adds AI-generated responsed to more complex user responses.

This example uses PicoCSS, a CSS framework that helps with simplicity. https://picocss.com/
In addition, it uses the AI Foundry Library that build on Data Foundry functionality. For information on how to use this library, take a look at the Github documentation.
The library: https://github.com/jortwi/AI-Foundry-Library
Data Foundry: https://data.id.tue.nl/

# Functions

Different reusable functions are used:

`sendMessage()` to 'send' user input, and provide a response

`userChoice(choice)` to provide a different response for each of the three options provided

`addMessage(type, input)` to place add the messages to the screen. For `type`, choose between `'user'` or `'assistant'`. This will place the message either to the right or left side of the screen. for `input`, provide the text to be placed on the screen.
