## test greet with help example 1
* greet: hello
    - utter_greet
* help: What can you help me with
    - utter_help

## test greet with help example 2
* greet: hello
    - utter_greet
* help: I need some help
    - utter_help

## test greet with goodbye
* greet: hello
    - utter_greet
* goodbye: bye
    - utter_goodbye

## test greet with bot challenge and bye
* greet: hello
    - utter_greet
* bot_challenge: Are you a bot?
    - utter_iamabot
* goodbye: bye
    - utter_goodbye