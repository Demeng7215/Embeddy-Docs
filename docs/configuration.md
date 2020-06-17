# Configuration
In this section, you will be shown how to properly configure your bot and what every option in your settings.yml file does.

### bot-token
The token of your bot application, found on the [Discord Developer Portal](https://discord.com/developers/applications). Instructions on how obtain this was explained in the Installation section.

### command-prefix
The prefix of your bot that is used for commands. This configures the string that must be included in front of every command in order for it to be recognized as a command. For example, setting the prefix to "-" will make the post command "-post" and setting the prefix to "!!!" will make the post command "!!!post".

### color
This is the HEX color Embeddy will use in its built-in and hard-coded embed messages such as the "Post Success" message.

### status-type
The bot's activity type. This should be either DEFAULT (playing), WATCHING, or LISTENING.

### status-text
The text for the bot's activity that is displayed after the status type. For example, setting this to "Minecraft" and having your status-type as DEFAULT will show "Playing Minecraft".

### admin-role-name
The NAME (not ID) of the role that is able to create and edit embeds.
