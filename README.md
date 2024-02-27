# kawai
from telegram.ext import Updater

def main():
    # Prompt the user to enter the bot token
    bot_token = input("Enter your bot token: ").strip()

    # Create the Updater with the bot token
    updater = Updater(bot_token)

    # Add your bot logic here...

    # Start the bot
    updater.start_polling()
    updater.idle
