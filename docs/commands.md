# Commands

## post {#channel} {embed}
**Description:** Posts a new embed message in the specified channel.<br>
**Aliases:** None.<br>
**Parameters:**
* {#channel} : The channel the embed should be posted in. You must tag this channel.
* {embed} : The name of the embed that will be posted. This is the file name of the embed's configuration file in the embeds folder without the .yml extension.

## edit {#channel} {message} {embed}
**Description:** Changes the embed of the specified message in the specified channel to the specified embed.<br>
**Aliases:** set, change<br>
**Parameters:**
* {#channel} : The channel that contains the message you wish to edit. You must tag this channel.
* {message} : The ID of the message you wish to edit.
* {embed} : The name of the embed that the old embed will be replaced with. This is the file name of the embed's configuration file in the embeds folder without the .yml extension.

## raw {text}
**Description:** Converts the provided text to a raw format that can be used in the configuration files.
