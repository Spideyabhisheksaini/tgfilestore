# File Sharing Bot Modified Version

<b>A Telegram Special File Sharing Bot Who Made A Link Of File And You Can Access File Through Link.</b>



### Features
- File sharing modified version made by - [@Its_Oreki_Hotarou](https://t.me/Its_Oreki_Hotarou)**
- Fully customisable.
- Two Force Sub Channels.
- Also working on Render Or Koyeb.
- Customisable welcome & Forcesub messages.
- More than one Posts in One Link.
- Can be deployed on heroku directly.

### Setup

- Add the bot to Database Channel with all permission
- Add bot to ForceSub channel as Admin with Invite Users via Link Permission if you enabled ForceSub 

##
### Installation
#### Deploy on Heroku
**BEFORE YOU DEPLOY ON HEROKU, YOU SHOULD FORK THE REPO AND CHANGE ITS NAME TO ANYTHING ELSE**<br>
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)</br>

##
## Installation
#### Deploy on Render
<b>BEFORE DEPLOY ON RENDER, FORK REPO EDIT CONFIG, CREATE NEW WEB-SERVICE ADD VARIABLES AND ADD MONITOR THATS IT</b>

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com)

##
#### Deploy in your VPS
````bash
git clone https://github.com/Sahil0976/MultiForce-Sub
cd File-Sharing-Bot
pip3 install -r requirements.txt
# <Create config.py appropriately>
python3 main.py
````

### Admin Commands

```
start - start the bot or get posts
batch - create link for more than one posts
genlink - create link for one post
users - view bot statistics
broadcast - broadcast any messages to bot users
stats - checking your bot uptime
help - For Help
about - about bot
```

### Variables

* `API_HASH` Your API Hash from my.telegram.org
* `APP_ID` Your API ID from my.telegram.org
* `TG_BOT_TOKEN` Your bot token from @BotFather
* `OWNER_ID` Must enter Your Telegram Id
* `CHANNEL_ID` Your Channel ID eg:- -100xxxxxxxx
* `DB_URL` Your mongo db url
* `DB_NAME` Your mongo db session name
* `ADMINS` Optional: A space separated list of user_ids of Admins, they can only create links
* `START_MSG` Optional: start message of bot, use HTML and <a href='https://github.com/codexbotz/File-Sharing-Bot/blob/main/README.md#start_message'>fillings</a>
* `FORCE_SUB_MESSAGE`Optional:Force sub message of bot, use HTML and Fillings
* `FORCESUB_CHANNEL` Optional: ForceSub Channel ID, leave 0 if you want disable force sub
* `FORCESUB_CHANNEL2` Optional: ForceSub Channel ID, leave 0 if you want disable force sub
* `PROTECT_CONTENT` Optional: True if you need to prevent files from forwarding
* `START_PIC` A pic with start message
* `FORCE_PIC` A pic with forcesub message

### Extra Variables

* `CUSTOM_CAPTION` put your Custom caption text if you want Setup Custom Caption, you can use HTML and <a href='https://github.com/CodeXBotz/File-Sharing-Bot/blob/main/README.md#custom_caption'>fillings</a> for formatting (only for documents)
* `DISABLE_CHANNEL_BUTTON` Put True to Disable Channel Share Button, Default if False
* `BOT_STATS_TEXT` put your custom text for stats command, use HTML and <a href='https://github.com/codexbotz/File-Sharing-Bot/blob/main/README.md#custom_stats'>fillings</a>
* `USER_REPLY_TEXT` put your text to show when user sends any message, use HTML


### Fillings
#### START_MESSAGE | FORCE_SUB_MESSAGE

* `{first}` - User first name

#### CUSTOM_CAPTION

* `{filename}` - file name of the Document
* `{previouscaption}` - Original Caption

#### CUSTOM_STATS

* `{uptime}` - Bot Uptime

**Star this Repo if you Liked it ⭐⭐⭐**

