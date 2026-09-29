## Working of Basic Chatbot

This is a simple rule-based chatbot made in Python.

First, the program creates a function called `chatbot()`. This function contains all the instructions for the chatbot.

When the chatbot starts, it displays a welcome message for the user. Then, a `while` loop is used to keep the chatbot running and continuously take input from the user.

The user enters a message such as `hello`, `how are you`, or `bye`. The program uses the `input()` function to take the user's message. The `lower()` function converts the message into lowercase so that the program can easily compare it with the predefined messages.

The program then uses `if-elif-else` statements to check the user's input.

If the user enters `hello`, the chatbot replies with `Hi!`.

If the user enters `how are you`, the chatbot replies with `I'm fine, thanks!`.

If the user enters `bye`, the chatbot replies with `Goodbye!` and the `break` statement stops the loop and ends the chatbot.

If the user enters any other message that is not predefined, the chatbot replies with `Sorry, I don't understand.`


