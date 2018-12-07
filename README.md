# discord-keyword-alerts
A Discord bot to alert members with a role when certain keywords are matched.

This bot mentions a specified role whenever a keyword match is found. The bot only works for embed messages and not normal user messages, as it's main purpose is to support Discord based cook groups. 

### Usage:
Keyword matches are determined based on a specified list of keywords and negative keywords. If any of the negative keywords match, the message will be ignored. You can set up your keywords in "keywords.txt" and negative keywords in "negatives.txt". If you want to use multiple words (i.e. define a keyword set), separate words with '+' in between (ex. air+jordan+1).

You must create a Discord bot and get its token, which should be put in "token.txt". A full guide on how to do this, with images, can be found [here](https://github.com/Chikachi/DiscordIntegration/wiki/How-to-get-a-token-and-channel-ID-for-Discord).

You must set up which channels you want to monitor for the keywords. List them 1 per line (example included in the .txt file).

Lastly, you must define which role to mention when a keyword match is detected. You can do this by simply entering the role you want to mention in "role.txt".

All settings can be changed on the fly so you don't have to restart the script if you want to change something.

### Screenshot:
![NERYS Example](https://i.gyazo.com/4a08077d54abfc90326f7639695955b6.png)
