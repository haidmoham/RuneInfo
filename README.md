<div align="center">
<p><img src="https://raw.githubusercontent.com/AoDude/RuneInfo/master/runeinfo.png" /></p>
<p>Documentation for RuneInfo, the RuneScape Discord Chat-Bot</p>
<p><a href="https://discordapp.com/oauth2/authorize?client_id=169116208342237184&permissions=268528640&scope=bot"><b>Invite RuneInfo to your Discord Guild</b></a></p>
<p><a href="https://discord.gg/TrDnKtQ"><b>Join the Official Discord Guild</b></a></p>
</div>


>The above is a **copy of a link** generated requesting the minimum permissions required to use every command **at the time**. I know not all permissions are right for every server, so don't be afraid to uncheck any of the boxes. If you try to use a command that requires more permissions than the bot is granted, it will let you know.

---

# Commands

- [Admin Commands](#admin-commands)
  - [Guild Settings](#guild-settings)
- [General Commands](#general-commands)
  - [Misc](#misc)
  - [Chat Bot Info](#chat-bot-info)
  - [User Settings](#user-settings)
- [Runescape Commands](#runescape-commands)
  - [Game Info](#game-info-1)
  - [PVM](#pvm)
  - [Repeatables](#repeatables)
  - [User Info](#user-info-1)
- [OSRS Commands](#osrs-commands)
  - [Game Info](#game-info)
  - [User Info](#user-info)

  
    
**Key** | **Info**
------------ | -------------
**Usage Parameters** | `<required> [optional]`
**Aliases** | `!(command|alias)`
**Prefix** | configurable[default = `!`], `@RuneInfo#5879`

## Admin Commands

### Guild Settings

#### Disablecommand
>**Description:** Disables the command in this guild.

>**Usage:** `!disablecommand <commandname:str>`

#### Enablecommand
>**Description:** Enables the command in this guild.

>**Usage:** `!enablecommand <commandname:str>`

#### Leave-channel
>**Description:** Sets the Read & Send permission for RuneInfo to deny in the current channel.

>**Usage:** `!leave-channel`

#### Setprefix
>**Description:** Sets the prefix for this guild.

>**Usage:** `!setprefix <prefix:str>`

## General Commands

### Misc

#### Twitch
>**Description:** Displays twitch information based on <Twitch_Username>.

>**Usage:** `!twitch <TwitchUsername:str>`

### Chat Bot Info

#### Github/Version/About
>**Description:** Displays info about the Author and Recent updates.

>**Usage:** `!(github|version|about)`

#### Help/Commands
>**Description:** Display help for a command.

>**Usage:** `!(help|commands) [Command:str]`

#### Info/Uptime
>**Description:** Displays info and stats about the bot.

>**Usage:** `!(info|uptime)`

#### Invite
>**Description:** Displays the join server link of the bot.

>**Usage:** `!invite`

#### Ping
>**Description:** Runs a connection test to Discord.

>**Usage:** `!ping`

#### Pinhelp
>**Description:** Pins the most up to date help message, and removes previous pinned RuneInfo messages.

>**Usage:** `!pinhelp`

### User Settings

#### Set07rsn
>**Description:** Associates your OSRS Username to your Discord ID, allowing you to run OSRS commands without the need of typing your username.

>**Usage:** `!set07rsn <Username:str{,12}>`

#### Setrsn
>**Description:** Associates your RS3 Username to your Discord ID, allowing you to run RS3 commands without the need of typing your username.

>**Usage:** `!setrsn <Username:str{,12}>`

## Runescape Commands

### Game Info

#### Arc
>**Description:** Displays the current arc rotations.

>**Usage:** `!arc`

#### Dnd/D&d
>**Description:** Displays the current weekly Distraction and Diversion that rewards you a free key.

>**Usage:** `!(dnd|d&d)`

#### Event
>**Description:** Displays the next event, on the RuneScape community event calendar.

>**Usage:** `!event`

#### Geadditions
>**Description:** Displays the new items added to the GE since the previous update.

>**Usage:** `!geadditions`

#### Jot/Jackoftrades
>**Description:** Displays how much XP you'd gain from Jack of Trades based on type and skill level.

>**Usage:** `!(jot|jackoftrades) <Normal|Master|Supreme|Legendary> <Level:int{1,120}>`

#### Lamp/Xplamp
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

>**Usage:** `!pengs <Points:int{1,50}> [Level:int{1,120}]`

#### Podcast
>**Description:** Displays the most recent RuneScape Podcast.

>**Usage:** `!podcast`

#### Portables/Portable
>**Description:** Displays the current locations of the Portables FC Worlds.

>**Usage:** `!(portables|portable)`

#### Price
>**Description:** Displays the current grand exchange info for <Item>

>**Usage:** `!price <ItemID:int|ItemName:str>`

#### Reddit
>**Description:** Displays the trending reddit posts.

>**Usage:** `!reddit`

#### Reset
>**Description:** Displays how long until reset time.

>**Usage:** `!reset`

#### Rsw/Wiki
>**Description:** Linkifies the search term on the RuneScape Wikia.

>**Usage:** `!(rsw|wiki) <SearchTerm:str>`

#### Statues
>**Description:** Displays how much XP you'd gain in various skills from monthly god statues.

>**Usage:** `!statues <Username:rsn>`

#### Thaler/Minigame/Minigames/Spotlight
>**Description:** Displays the current spotlighted minigame.

>**Usage:** `!(thaler|minigame|minigames|spotlight) [Minigame:str]`

#### Time
>**Description:** Displays the current game-time.

>**Usage:** `!time`

#### Viswax/Vis
>**Description:** Displays the current Vis Wax Combinations.

>**Usage:** `!(viswax|vis)`

#### Vos
>**Description:** Displays the current Voice of Seren districts.

>**Usage:** `!vos`

#### Youtube
>**Description:** Displays the most recent RuneScape YouTube Upload.

>**Usage:** `!youtube`

### PVM

#### Araxxor/Araxxi/Rax/Spooder
>**Description:** Displays the current Araxxor rotation.

>**Usage:** `!(araxxor|araxxi|rax|spooder)`

#### Pvm
>**Description:** Displays the current PVM rotations.

>**Usage:** `!pvm`

#### Pvmstaples
>**Description:** Displays what pvm tools are useable, via levels alone..

>**Usage:** `!pvmstaples <Username:rsn>`

#### Pvmstats
>**Description:** Displays only pvm stats.

>**Usage:** `!pvmstats <Username:rsn>`

#### Rots
>**Description:** Displays the current Rise of the Six rotation.

>**Usage:** `!rots`

#### Vorago/Rago
>**Description:** Displays the current Vorago rotation.

>**Usage:** `!(vorago|rago)`

### Repeatables

#### Bigchin
>**Description:** Displays when the next Big Chinchompa will be.

>**Usage:** `!bigchin`

#### Cache
>**Description:** Displays when the next Guthixian Cache will be.

>**Usage:** `!cache`

#### Circus
>**Description:** Displays the current location for the Circus.

>**Usage:** `!circus`

#### Invasion/Trollinvasion/Troll
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

#### Sinkhole/Sinkholes
>**Description:** Displays when the next Sinkhole will be.

>**Usage:** `!(sinkhole|sinkholes)`

#### Warbands/Wbs
>**Description:** Displays the time until the next Warbands.

>**Usage:** `!(warbands|wbs)`

### User Info

#### Alog
>**Description:** Displays the adventure log of the username given.

>**Usage:** `!alog <Username:rsn>`

#### Combat/Cmb
>**Description:** Display RS3 combat level, and tells you what you would need to increase your combat level.

>**Usage:** `!(combat|cmb) <Username:rsn>`

#### Gainz
>**Description:** Display RS3 XP gained recently of the username given. Credit RuneClan for data.

>**Usage:** `!gainz <Username:rsn>`

#### Playerinfo/Getclan
>**Description:** Displays player info of the username provided.

>**Usage:** `!(playerinfo|getclan) <Username:rsn>`

#### Quests
>**Description:** Display RS3 quests started and eligible of the username given.

>**Usage:** `!quests <Username:rsn>`

#### Stats-hcim/Hs-hcim
>**Description:** Display RS3 Hardcore Ironman stats of the username given.

>**Usage:** `!(stats-hcim|hs-hcim) <Username:rsn>`

#### Stats-im/Hs-im
>**Description:** Display RS3 Ironman stats of the username given.

>**Usage:** `!(stats-im|hs-im) <Username:rsn>`

#### Stats/Hs
>**Description:** Display RS3 stats of the username given.

>**Usage:** `!(stats|hs) <Username:rsn>`

#### Vstats/Vhs
>**Description:** Displays virtual RS3 stats of the username given.

>**Usage:** `!(vstats|vhs) <Username:rsn>`

#### Wsid
>**Description:** `What Should I Do?` Returns a random object you should work on. Optionally, providing your username will provide a more personalised object to work on.

>**Usage:** `!wsid [Username:rsn]`

## OSRS Commands

### Game Info

#### 07price
>**Description:** Displays the current OSRS grand exchange info for <Item>

>**Usage:** `!07price <ItemID:int|ItemName:str>`

#### 07reddit
>**Description:** Displays the trending osrs reddit posts.

>**Usage:** `!07reddit`

#### 07rsw/07wiki
>**Description:** Linkifies the search term on the OSRS Wikia.

>**Usage:** `!(07rsw|07wiki) <Search_Term:str>`

### User Info

#### 07combat/07cmb
>**Description:** Display OSRS combat level, and what it would take to increase it.

>**Usage:** `!(07combat|07cmb) <Username:osrsn>`

#### 07gainz/Osgainz
>**Description:** Display OSRS XP gained recently of the username given. Credit RuneClan for data.

>**Usage:** `!(07gainz|osgainz) <Username:osrsn>`

#### 07stats-dm/07hs-dm
>**Description:** Display OSRS Deadman Mode stats of the username given.

>**Usage:** `!(07stats-dm|07hs-dm) <Username:osrsn>`

#### 07stats-dms/07hs-dms
>**Description:** Display OSRS Deadman Seasonal stats of the username given.

>**Usage:** `!(07stats-dms|07hs-dms) <Username:osrsn>`

#### 07stats-hcim/07hs-hcim
>**Description:** Display OSRS Ultimate Ironman stats of the username given.

>**Usage:** `!(07stats-hcim|07hs-hcim) <Username:osrsn>`

#### 07stats-im/07hs-im
>**Description:** Display OSRS Ironman stats of the username given.

>**Usage:** `!(07stats-im|07hs-im) <Username:osrsn>`

#### 07stats-uim/07hs-uim
>**Description:** Display OSRS Ultimate Ironman stats of the username given.

>**Usage:** `!(07stats-uim|07hs-uim) <Username:osrsn>`

#### 07stats/07hs
>**Description:** Display OSRS stats of the username given.

>**Usage:** `!(07stats|07hs) <Username:osrsn>`
