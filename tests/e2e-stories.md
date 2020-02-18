## test greet with help example 1
* greet: hello
    - greet
* help: What can you help me with
    - help

## test greet with help example 2
* greet: hello
    - greet
* help: I need some help
    - help

## test greet with goodbye
* greet: hello
    - greet
* goodbye: bye
    - utter_goodbye

## test greet with bot challenge and bye
* greet: hello
    - greet
* bot_challenge: Are you a bot?
    - utter_iamabot
* goodbye: bye
    - utter_goodbye