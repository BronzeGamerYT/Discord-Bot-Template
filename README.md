### Discord Bot Template

I will teach you how to create a Discord bot, this is a template only.

### Setup

Go to .env file and paste yout token. It should look like this

TOKEN = [YOUR_TOKEN_HERE]

### Pre-Setup
If you don't already have a discord bot, click [here](https://discordapp.com/developers/), accept any prompts then click "New Application" at the top right of the screen.  Enter the name of your bot then click accept.  Click on Bot from the panel from the left, then click "Add Bot."  When the prompt appears, click "Yes, do it!" 
![Left panel](https://i.imgur.com/hECJYWK.png)

Then, click copy under token to get your bot's token. Your bot's icon can also be changed by uploading an image.

![Bot token area](https://i.imgur.com/da0ktMC.png)


### Prefix 

To change the prefix of the bot, go to main.py and change your prefix in line 12. It should look like this

client = commands.Bot(command_prefix = '!') 

### Credits

All THE CREDITS GO TO BRONZE GAMER