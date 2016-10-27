# RuneInfo
Documentation for a Closed-Source Runescape Discord Chat-Bot

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

## General Commands

### Chat Bot Info

#### Help
>**Description:** Dm's a help message containing all commands that can be used in the givin channel. Optionally providing a command will display the Description and Usage for the given command.

>**Usage:** `!help [Command:str]`

#### Info
>**Description:** Displays info and stats about the bot.

>**Usage:** `!info`

#### Leave-Channel
>**Description:** Sets the Read/Write permission for RuneInfo to deny in the current channel. (Only guild admins may use this) Requires Manage Channel Permissions.

>**Usage:** `!leave-channel`

#### Ping
>**Description:** Runs a connection test to Discord.

>**Usage:** `!ping`

#### PinHelp
>**Description:** Pins the most up to date help message. If one already exists, updates the existing one.

>**Usage:** `!pinhelp`

#### Uptime
>**Description:** Returns the amount of time since the bot started.

>**Usage:** `!uptime`

#### Version
>**Description:** Displays the current version of the bot.

>**Usage:** `!version`

#### Gameboard
>**Description:** Displays how many people are playing what game.

>**Usage:** `!gameboard`

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

#### 07stats-dm
>**Description:** Display OSRS Deadman Mode stats of the username given.

>**Usage:** ` !(07stats-dm|07hs-dm) <Username:str>`

#### 07stats-dms
>**Description:** Display OSRS Deadman Seasonal stats of the username given.
>**Usage:** ` !(07stats-dms|07hs-dms) <Username:str>`

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
#### dnd
>**Description:** Displays the current weekly Distraction and Diversion that rewards you a free key.

>**Usage:** `!(dnd|d&d)`

#### event
>**Description:** Displays the next event, on the RuneScape community event calendar.

>**Usage:** `!event`

#### geadditions
>**Description:** Displays the new items added to the GE since the previous update.

>**Usage:** `!geadditions`

#### jot
>**Description:** Displays how much XP you'd gain from Jack of Trades based on type and skill level.

>**Usage:** `!(jot|jackoftrades) <Normal|Master|Supreme|Legendary> <Level:int{1,120}>`

#### lamp
>**Description:** Displays how much XP you'd get from a lamp based on Level.

>**Usage:** `!(lamp|xplamp) <Small|Medium|Large|Huge> <Level:int{1,120}>`

#### nemi
>**Description:** Displays the most recent 9/9 Nemi Forest. 

>**Usage:** `!nemi`

#### news
>**Description:** Displays the most recent RuneScape News.

>**Usage:** `!news`

#### pengs
>**Description:** Displays how much XP or Coins you'd gain from penguins.

>**Usage:** `!pengs <Points:int> [Level:int{1,120}]`

#### podcast
>**Description:** Displays the most recent RuneScape Podcast.

>**Usage:** `!podcast`

#### portables
>**Description:** Displays the current locations of the Portables FC Worlds.

>**Usage:** `!(portables|portable) [Fletchers|Crafters|Braziers|Sawmills|Forges|Ranges|Wells]`

#### price
>**Description:** Displays the current grand exchange info for <Item>

>**Usage:** `!price <ItemID:int|ItemName:str>`

#### reset
>**Description:** Displays how long until reset time.

>**Usage:** `!reset`

#### rsw
>**Description:** Linkifies the search term on the RuneScape Wikia.

>**Usage:** `!rsw <SearchTerm:str>, [...]`

#### statues
>**Description:** Displays how much XP you'd gain in various skills from monthly god statues.

>**Usage:** `!statues <Username:str>`

#### thaler
>**Description:** Displays the current spotlighted minigame.

>**Usage:** `!(thaler|minigame|minigames|spotlight) [Minigame:str]`

#### time
>**Description:** Displays the current game-time.

>**Usage:** `!time`

#### viswax
>**Description:** Displays the current Vis Wax Combinations.

>**Usage:** `!(viswax|vis)`

#### vos
>**Description:** Displays the current Voice of Seren districts.

>**Usage:** `!vos`

#### youtube
>**Description:** Displays the most recent RuneScape YouTube Upload.

>**Usage:** `!youtube`

###PVM

#### araxxor
>**Description:** Displays the current Araxxor rotation.

>**Usage:** `!(araxxor|araxxi|rax)`

#### pvm
>**Description:** Displays the current PVM rotations.

>**Usage:** `!pvm`

#### pvmstats
>**Description:** Displays only pvm stats.

>**Usage:** `!pvmstats <Username:str>`

#### pvmstaples
>**Description:** Displays what pvm tools are useable, via levels alone.

>**Usage:** `!pvmstaples <Username:str>`

#### rots
>**Description:** Displays the current Rise of the Six rotation.

>**Usage:** `!rots`

#### vorago
>**Description:** Displays the current Vorago rotation.

>**Usage:** `!(vorago|rago)`

###Repeatables

#### bigchin
>**Description:** Displays when the next Big Chinchompa will be.

>**Usage:** `!bigchin`

#### cache
>**Description:** Displays when the next Guthixian Cache will be.

>**Usage:** `!cache`

#### circus
>**Description:** Displays the current location for the Circus.

>**Usage:** `!circus`

#### invasion
>**Description:** Determine how much XP you get for completing troll invasion based on <Level>.

>**Usage:** `!(invasion|trollinvasion|troll) <Level:int{1,120}>`

#### penglocs
>**Description:** Displays the current location of the Penguins on World 60.

>**Usage:** `!penglocs`

#### raven
>**Description:** Displays when the next Raven will spawn in Prifddinas.

>**Usage:** `!raven`

#### runesphere
>**Description:** Displays the time until the next runesphere.

>**Usage:** `!runesphere`

#### sinkhole
>**Description:** Displays when the next Sinkhole will be.

>**Usage:** `!(sinkhole|sinkholes)`	

#### warbands
>**Description:** Displays the time until the next Warbands.

>**Usage:** `!(warbands|wbs)`

###User Info

#### alog
>**Description:** Displays the adventure log of the username given.

>**Usage:** `!alog <Username:str>`

#### combat
>**Description:** Display RS3 combat level, and tells you what you would need to increase your combat level.

>**Usage:** `!(combat|cmb) <Username:str>`

#### getclan
>**Description:** Display RS3 clan of the username given.

>**Usage:** !getclan <Username:str>

#### online
>**Description:** Displays online status of the username given, or total player count if no username is provided.

>**Usage:** `!online [Username:str], [...]`

#### stats-hcim
>**Description:** Display RS3 Hardcore Ironman stats of the username given.

>**Usage:** `!(stats-hcim|hs-hcim) <Username:str>`

#### stats-im
>**Description:** Display RS3 Ironman stats of the username given.

>**Usage:** `!(stats-im|hs-im) <Username:str>`

#### stats
>**Description:** Display RS3 stats of the username given.

>**Usage:** `!(stats|hs) <Username:str>`

#### wsid
>**Description:** `What Should I Do?` Returns a random object you should work on. Optionally, providing your username will provide a more personalised object to work on.

>**Usage:** `!wsid [Username:str]`

