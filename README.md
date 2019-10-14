# Elementar, meu caro Watson

Watson Bot for the Intelligent Systems discipline at UFPE

The discipline required the development of a bot, it was recommended the use of IBM's Watson.

This bot is the implementation of a game based on Dark Stories. You are presented with 3 murder mysteries and you must interact with the scenario in order to gain more information and solve them.

It utilizes Watson to process Natural Language and identify relevant sentences to each of the scenarios. The implementation also includes a tutorial so players are familiar with the way commands are processed. Options for help, hints and answers to some questions are also available.

This bot was graded 100%.

# How to run on IBM's Watson

Open the Watson Interface and import the skill-Watson.json of the /bot folder in this repository.
Afterwards, you'll be able to make any modifications and test the bot simultaneously.

# How to run on Telegram

Currently, there's a bot running the file under the name of "Elementar, meu caro Watson", it can also be found via @SistemasGeniais_bot.

If you wish to run your own instance on telegram, you'll need to load it on Watson and utilize IBM's Node-RED.
The steps are better described on this link:

``` https://developer.ibm.com/recipes/tutorials/how-to-create-a-watson-chatbot-on-nodered/ ```

Note that it's important for the instance of the bot to be able to handle multiple users at once, so make sure to check the msg.user option on Node-RED.

# Notes
This project was implemented in Portuguese and it's the only available language.
