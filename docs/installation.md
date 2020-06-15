# Installation

## Prerequisites
* Java 8 or above.
* Knowledge on how to use Discord.

## Creating the Bot Account
1. Go to [Discord's Developer Portal](https://discord.com/developers/applications).
2. Create a new application. Set the username and, optionally, the profile picture.
3. On the left menu, click Bot.
4. Click Create a Bot and set its username and, optionally, the profile picture.
5. Untick "Public Bot" so other people can't just invite your bot onto their server.
6. Click Copy Token- you will need the bot's token for later.
7. Go to OAuth and for scope, select "bot". For permission, tick either Administrator or all the permissions the bot needs (send messages, embed links).
8. Go to the link that is generated and follow the instructions to add the bot to the server of your choice.
9. Congratuluations! You have successfully created a bot account.

## Starting the Bot
1. Run the StartEmbeddy.bat file (Windows) or execute ```java -jar Embeddy.jar```.
2. The bot will start loading. If this is your first time, a settings.yml and an embeds folder will be generated.
3. The bot will shut down due to a "Failed to log in to bot account" error. This is perfectly normal- proceed to the next steps.
4. Go to settings.yml and where it asks for the bot's token, paste the token you copied from step 6 of Creating the Bot Account. Make sure the token is surrounded with "double quotes".
6. Save the file and restart the bot. Embeddy should now be successfully enabled if you followed all the steps correctly!
7. Congratulations! Your bot is now up and running. You can confirm this by going to your Discord server and checking the bot's status. It should now be Online and have the default status of "Watching embed messages" (unless you have changed it).
