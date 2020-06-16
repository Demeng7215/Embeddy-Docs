# Creating Embeds

## Getting Started
1. Go to the bot's directory and open the "embeds" folder.
2. Create a new file called name.yml. Replace "name" with whatever you wish to identify your embed with (eg. information.yml).
3. Copy and paste this example file that uses and explains everything Embeddy can do with embeds into the newly created file: [CLICK HERE](https://github.com/Demeng7215/Embeddy-Docs/blob/master/example.yml)
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
