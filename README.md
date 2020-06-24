# Insurgency Sandstorm DiscordChat
This let your discord bot send message to your insurgency sandstorm in game chat.<br>
You have to use this with [Advanced Chat](https://insurgencysandstorm.mod.io/advanced-chat) mod<br><br>

To use this, you must install nodejs and npm on your server. You can try and test it on your computer but don't recommend because your bot will need to run 24/7. The moment you close your bot, users on discord won't able to send any chat message to in-game or receive any message.<br><br>

You will need to `npm install` to install the require lib for this discord bot.<br>
Make sure you edit your [configs.json](https://github.com/zWolfi/INS_Sandstorm_DiscordChat/blob/master/configs.json) file and put in your server rcon IP, port, password, your bot token, and your sandstorm log file path.<br>
Make sure you have the right text channel and the log file path exist. Otherwise, you will get an error.<br><br>

After all that, all you have to do is to run the main.js from the server folder and you will have to invite your bot to your discord server. Bot will show up in your discord server and you will have to give the permission to the bot strictly. Otherwise the bot will send all the messages from all the text channel to in game chat.
