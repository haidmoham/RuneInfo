<div align="center">
<p><img src="https://raw.githubusercontent.com/AoDude/RuneInfo/master/runeinfo.png" /></p>
<p>Documentation for RuneInfo, the RuneScape Discord Chat-Bot</p>
<p><a href="https://discordapp.com/oauth2/authorize?&client_id=169116208342237184&scope=bot&permissions=268561408"><b>Invite RuneInfo to your Discord Guild</b></a></p>
<p><a href="https://discord.gg/TrDnKtQ"><b>Join the Official Discord Guild</b></a></p>
</div>


>The above is a **copy of a link** generated requesting the minimum permissions required to use every command **at the time**. I know not all permissions are right for every server, so don't be afraid to uncheck any of the boxes. If you try to use a command that requires more permissions than the bot is granted, it will let you know.

---

# Commands

- [General Commands](#general-commands)
  - [Chat Bot Info](#chat-bot-info)
  - [Misc](#misc)
- [OSRS Commands](#osrs-commands)
  - [Game Info](#game-info)
  - [User Info](#user-info)
- [Runescape Commands](#runescape-commands)
  - [Game Info](#game-info-1)
  - [PVM](#pvm)
  - [Repeatables](#repeatables)
  - [User Info](#user-info-1)
  
    
**Key** | **Info**
------------ | -------------
**Usage Parameters** | `<required> [optional]`
**Aliases** | `!(command|alias)`

## General Commands

### Chat Bot Info

#### GitHub/Version/About
>**Description:** Displays the current version info of the bot.

>**Usage:** `!(github|version|about)`

#### Help
>**Description:** Dm's a help message containing all commands that can be used in the given channel. Optionally providing a command will display the Description and Usage for the given command.

>**Usage:** `!(help|commands) [Command:str]`

#### Info/Uptime
>**Description:** Displays info and stats about the bot.

>**Usage:** `!(info|uptime)`

#### Leave-Channel
>**Description:** Sets the Read/Write permission for RuneInfo to deny in the current channel. (Only guild admins may use this) Requires Manage Channel Permissions.

>**Usage:** `!leave-channel`

#### Ping
>**Description:** Runs a connection test to Discord.

>**Usage:** `!ping`

#### PinHelp
>**Description:** Pins the most up to date help message. If one already exists, updates the existing one.

>**Usage:** `!pinhelp`

### Misc

#### Twitch
>**Description:** Displays twitch information based on <Twitch_Username>.

>**Usage:** `!twitch <TwitchUsername:str>`

## OSRS Commands

### Game Info

#### 07price
>**Description:** Displays the current OSRS grand exchange info for <Item>

>**Usage:** `!07price <Item:str>`

#### 07rsw
>**Description:** Linkifies the search term on the OSRS Wikia.

>**Usage:** `!07rsw <Search_Term>, [...]`

###User Info

#### 07combat
>**Description:** Display OSRS combat level, and what it would take to increase it.

>**Usage:** `!(07combat|07cmb) <Username:str>`

#### 07gainz
>**Description:** Display OSRS XP gained recently of the username given.

>**Usage:** `!(07gainz|osgainz) <Username:str>`

#### 07stats-dm
>**Description:** Display OSRS Deadman Mode stats of the username given.

>**Usage:** `!(07stats-dm|07hs-dm) <Username:str>`

#### 07stats-dms
>**Description:** Display OSRS Deadman Seasonal stats of the username given.

>**Usage:** ` !(07stats-dms|07hs-dms) <Username:str>`

#### 07stats-hcim
>**Description:** Display OSRS Hardcore Ironman stats of the username given.

>**Usage:** `!(07stats-hcim|07hs-hcim) <Username:str>`

#### 07stats-im
>**Description:** Display OSRS Ironman stats of the username given.

>**Usage:** `!(07stats-im|07hs-im) <Username:str>`

#### 07stats-uim
>**Description:** Display OSRS Ultimate Ironman stats of the username given.

>**Usage:** `!(07stats-uim|07hs-uim) <Username:str>`

#### 07stats
>**Description:** Display OSRS stats of the username given.

>**Usage:** `!(07stats|07hs) <Username:str>`

##Runescape Commands

###Game Info

#### Arc
>**Description:** Displays the current arc rotations.

>**Usage:** `!arc`

#### Dnd
>**Description:** Displays the current weekly Distraction and Diversion that rewards you a free key.

>**Usage:** `!(dnd|d&d)`

#### Event
>**Description:** Displays the next event, on the RuneScape community event calendar.

>**Usage:** `!event`

#### Geadditions
>**Description:** Displays the new items added to the GE since the previous update.

>**Usage:** `!geadditions`

#### Jot
>**Description:** Displays how much XP you'd gain from Jack of Trades based on type and skill level.

>**Usage:** `!(jot|jackoftrades) <Normal|Master|Supreme|Legendary> <Level:int{1,120}>`

#### Lamp
>**Description:** Displays how much XP you'd get from a lamp based on Level.

>**Usage:** `!(lamp|xplamp) <Small|Medium|Large|Huge> <Level:int{1,120}>`

#### Nemi
>**Description:** Displays the most recent 9/9 Nemi Forest. 

>**Usage:** `!nemi`

#### News
>**Description:** Displays the most recent RuneScape News.

>**Usage:** `!news`

#### Online
>**Description:** Displays online player count.

>**Usage:** `!online`

#### Pengs
>**Description:** Displays how much XP or Coins you'd gain from penguins.

>**Usage:** `!pengs <Points:int> [Level:int{1,120}]`

#### Podcast
>**Description:** Displays the most recent RuneScape Podcast.

>**Usage:** `!podcast`

#### Portables
>**Description:** Displays the current locations of the Portables FC Worlds.

>**Usage:** `!(portables|portable) [Fletchers|Crafters|Braziers|Sawmills|Forges|Ranges|Wells]`

#### Price
>**Description:** Displays the current grand exchange info for <Item>

>**Usage:** `!price <ItemID:int|ItemName:str>`

#### Reset
>**Description:** Displays how long until reset time.

>**Usage:** `!reset`

#### Rsw
>**Description:** Linkifies the search term on the RuneScape Wikia.

>**Usage:** `!rsw <SearchTerm:str>, [...]`

#### Statues
>**Description:** Displays how much XP you'd gain in various skills from monthly god statues.

>**Usage:** `!statues <Username:str>`

#### Thaler
>**Description:** Displays the current spotlighted minigame.

>**Usage:** `!(thaler|minigame|minigames|spotlight) [Minigame:str]`

#### Time
>**Description:** Displays the current game-time.

>**Usage:** `!time`

#### Viswax
>**Description:** Displays the current Vis Wax Combinations.

>**Usage:** `!(viswax|vis)`

#### Vos
>**Description:** Displays the current Voice of Seren districts.

>**Usage:** `!vos`

#### Youtube
>**Description:** Displays the most recent RuneScape YouTube Upload.

>**Usage:** `!youtube`

### PVM

#### Araxxor
>**Description:** Displays the current Araxxor rotation.

>**Usage:** `!(araxxor|araxxi|rax)`

#### Pvm
>**Description:** Displays the current PVM rotations.

>**Usage:** `!pvm`

#### Pvmstats
>**Description:** Displays only pvm stats.

>**Usage:** `!pvmstats <Username:str>`

#### Pvmstaples
>**Description:** Displays what pvm tools are useable, via levels alone.

>**Usage:** `!pvmstaples <Username:str>`

#### Rots
>**Description:** Displays the current Rise of the Six rotation.

>**Usage:** `!rots`

#### Vorago
>**Description:** Displays the current Vorago rotation.

>**Usage:** `!(vorago|rago)`

###Repeatables

#### Bigchin
>**Description:** Displays when the next Big Chinchompa will be.

>**Usage:** `!bigchin`

#### Cache
>**Description:** Displays when the next Guthixian Cache will be.

>**Usage:** `!cache`

#### Circus
>**Description:** Displays the current location for the Circus.

>**Usage:** `!circus`

#### Invasion
>**Description:** Determine how much XP you get for completing troll invasion based on <Level>.

>**Usage:** `!(invasion|trollinvasion|troll) <Level:int{1,120}>`

#### Penglocs
>**Description:** Displays the current location of the Penguins on World 60.

>**Usage:** `!penglocs`

#### Raven
>**Description:** Displays when the next Raven will spawn in Prifddinas.

>**Usage:** `!raven`

#### Runesphere
>**Description:** Displays the time until the next runesphere.

>**Usage:** `!runesphere`

#### Sinkhole
>**Description:** Displays when the next Sinkhole will be.

>**Usage:** `!(sinkhole|sinkholes)`	

#### Warbands
>**Description:** Displays the time until the next Warbands.

>**Usage:** `!(warbands|wbs)`

###User Info

#### Alog
>**Description:** Displays the adventure log of the username given.

>**Usage:** `!alog <Username:str>`

#### Combat
>**Description:** Displays RS3 combat level, and tells you what you would need to increase your combat level.

>**Usage:** `!(combat|cmb) <Username:str>`

#### Gainz
>**Description:** Display RS3 XP gained recently of the username given.

>**Usage:** `!gainz <Username:str>`

#### Playerinfo/Getclan
>**Description:** Displays player info of the username provided.

>**Usage:** `!(playerinfo|getclan) <Username:str>`

#### Quests
>**Description:** Display RS3 quests started and eligible of the username given.

>**Usage:** `!quests <Username:str>`

#### Stats-hcim
>**Description:** Displays RS3 Hardcore Ironman stats of the username given.

>**Usage:** `!(stats-hcim|hs-hcim) <Username:str>`

#### Stats-im
>**Description:** Displays RS3 Ironman stats of the username given.

>**Usage:** `!(stats-im|hs-im) <Username:str>`

#### Stats
>**Description:** Displays RS3 stats of the username given.

>**Usage:** `!(stats|hs) <Username:str>`

#### Vstats
>**Description:** Displays virtual RS3 stats of the username given.

>**Usage:** `!(vstats|vhs) <Username:str>`

#### Wsid
>**Description:** `What Should I Do?` Returns a random object you should work on. Optionally, providing your username will provide a more personalised object to work on.

>**Usage:** `!wsid [Username:str]`

