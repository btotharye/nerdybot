# nerdybot
A Chatbot for The Nerdy Python snake business being streamed over twitch as it is built.

# Steps To Bring Up Locally
1. Run `python3 -m venv venv` to create a virtualenv
2. Activate it `source venv/bin/activate`
3. Install requirements `pip install -r requirements.txt`
4. If doing local testing and such `pip install -r requirements-dev.txt`
5. `rasa train` to train our model.
6. `rasa shell --debug` to interact with our bot.

# Testing Locally
Ensure you have ran `pip install -r requirements-dev.txt` before these steps below.

`make lint` - does linting
`make types` - type checking
`make formatter` - uses black to fix formatting
`make validate` - uses rasa validate to validate training data.