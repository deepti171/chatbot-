# chatbot

Simple chatbot implementation with PyTorch.
For Customization for your own use case,Just modify intents.json

# Dependencies

You  need nltk:

pip install nltk
If you get an error during the first run, you also need to install nltk.tokenize.punkt: Run this once in your terminal:


import nltk
nltk.download('punkt')


# Customize

Have a look at intents.json. You can customize it according to your own use case. Just define a new tag, possible patterns, and possible responses for the chat bot. You have to re-run the training whenever this file is modified.

