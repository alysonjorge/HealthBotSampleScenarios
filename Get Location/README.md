# Get Location - getting user's geo location during conversation

This scenario sends a "shareLocation" event from the bot to the user, with the user's consent, the bot will get back the user's location

## Limitations 
 1. Works only with webchat channel
 2. requires a supporting html container page for the webchat app
 
## Usage
 1. Make sure you are using a supporing html container page for the webchat app, the supporting page will intercept the "shareLocation"       event from the bot, and will prompt the user for share location consent. once the user has approved, the location will be sent back to     the bot
 
 2. A reference for a supporting HTML page can be foun here (look at public/index.js):
 (https://github.com/Microsoft/HealthBotContainerSample)
