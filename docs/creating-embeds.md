# Creating Embeds

## Getting Started
1. Go to the bot's directory and open the "embeds" folder.
2. Create a new file called name.yml. Replace "name" with whatever you wish to identify your embed with (eg. information.yml).
3. Copy and paste this example file that uses and explains everything Embeddy can do with embeds into the newly created file:
```yaml
# The highlight color of your embed.
# Must be a valid HEX color code.
color: "#FFFFFF"

# The title of your embed.
title: "Example Embed"
# The URL that the user will be redirected to when the title is clicked.
title-url: "https://demeng.dev/"

# The "author" of the embed.
author: "Demeng"
# A URL to the author's icon- must be a raw image.
author-icon: "https://demeng.dev/branding/icon.png"
# The URL that the user will be redirected to when the author is clicked.
author-url: "https://demeng.dev/"

# The embed's content.
# This is a string list- each line means a new line in the description.
# Alternatively, you can use "\n".
description:
  - "This is the description of the embed."

# The image displayed in the top right of your embed.
# Must be a URL linking to a raw image.
thumbnail: "https://demeng.dev/branding/icon.png"
# The large image displayed at the bottom of your embed.
# Must be a URL linking to a raw image.
picture: "https://demeng.dev/branding/embeddy/icon.png"

# The footer text of your embed.
footer: "Embed Footer"
# A URL to the footer's icon- must be a raw image.
footer-icon: "https://demeng.dev/branding/embeddy/icon.png"

# true or false depending on if you wish to show the timestamp on the embed.
# This is the date the embed was posted and is displayed beside the footer.
show-timestamp: true

# A list of embed fields.
# Each field must be labelled by a unique string. It is recommended that you incrementing numbers.
# Title is the title of the field.
# Description is the content of the field.
# Inline must be either true or false depending on if you want to field to inline or not.
fields:
  1:
    title: "Field #1"
    description: "This is first field."
    inline: true
  2:
    title: "Field #2"
    description: "This is another field."
    inline: true
  3:
    title: "Field #3"
    description: "This is the last and final field."
    inline: true
```
4. Customize options to your liking. Make sure everything you do follows YAML format! If you wish to not have something (eg. author), simple delete that line from the configuration.
5. Save the file and go to your Discord server.
6. Execute the ```[PREFIX]post <#channel> <embed>``` command to post this embed! The <embed> argument is the name of the file you just created (without the .yml at the end).

## Simple Embed Example
This is an example configuration of how to create an extremely simple embed with only color, title, description, and footer.
```yaml
color: "#0398fc"
title: "Simple Embed"
description:
  - "Hello there! I am a simple embed."
  - "How is your day?"
footer: "Sent with Love Using Embeddy"
footer-icon: "https://demeng.dev/branding/embeddy/icon.png"
```
