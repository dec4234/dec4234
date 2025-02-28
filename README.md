<h1 align="center">Hi 👋, I'm dec</h1>
<h3 align="center">Java, Rust and C++ Developer</h3>

<p align="left"> <img src="https://komarev.com/ghpvc/?username=dec4234&label=Profile%20views&color=0e75b6&style=flat" alt="dec4234" /> </p>

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://twitter.com/dec4234" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="dec4234" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> </p>

<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=dec4234&show_icons=true&include_all_commits=true&count_private=true&theme=dark" alt="dec4234" /></p>

<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=dec4234&layout=compact" alt="dec4234 Languages" /></p>

# Projects

## Java

### [JavaDestinyAPI](https://github.com/dec4234/JavaDestinyAPI)
An API wrapper written in Java for the Bungie platform API. Useful for developers looking to retrieve stats and other information about users and clans inside of the game Destiny 2. Supports clan management such as kicking, banning, promoting and inviting as well using OAuth.

### [Benedict](https://github.com/dec4234/Benedict)
A Discord Bot using JDA and the JavaDestinyAPI to control my [Destiny 2 Clan](https://www.bungie.net/en/ClanV2?groupid=3074427). The bot supports several features related to clan management, most notably: Applications handled inside Discord, Discord role management and functionality to automatically detect people who leave. The bot has made it significantly easier to manage the clan as many tedious actions have been automated. I host it on a Raspberry Pi 4 8 GB at my house.

MongoDB is utilized to store information about each user including both Discord and Bungie IDs, join and leave dates, and usernames. This allows me to have access to all of the information needed to manage clan members.

### [StreamAlerter](https://github.com/dec4234/StreamAlerter)
StreamAlerter is a project I made to be able to detect when Youtubers start a live stream without using the Google API. Normally if you wanted to check for a Youtube livestream, you would have to use the Google API which is limited through quotas. This solution retrieves the web page using a channel ID and then checks for a specific link under a certain html tag. The only potential problem with this solution is bandwith usage, but it can mitigated by limiting the time between calls.

## Spigot Plugins (Java)

### [Pit Core 3](https://github.com/dec4234/PitCore3/)
The third iteration of a Spigot plugin for the semi-private minecraft server I help develop. This is the biggest project relating to Minecraft server development that I have undertaken.

The basic gameplay loop of the server relates around "Pits" where players can go to kill a lot of mobs in order to progress to the next highest pit. In order to be able to make this work, the plugin implements a custom mob spawning solution modeled off of Hypixel Skyblock's system. Whenever mobs are killed they are added to a list of dead mobs, then at a fixed interval all dead mobs are respawned. 

Additionally, MongoDB is used to store player information such as kills, deaths, money (shekels) and a Base64 encoded private vault. A public scoreboard using armor stand holograms is used to display the top 5 mob killers on each day. A sidebar scoreboard solution has also been implemented, using a system that I developed.

The server also utilizes command blocks built and managed by another user, Wildfire, to control the finer gameplay elements. The server is by no means amazing but it is a good game to play while at school.

### [DecsLoginSecurity2](https://github.com/dec4234/DecsLoginSecurity2)
DecsLoginSecurity is an offline mode security solution for offline mode servers. This plugin is used on the "The Pit" which is the same server as above.

All users are required to register a password and use it when logging in. Otherwise, any user with malicious intent could login under another player's name and wreak havoc.

### [DecsNPCs](https://github.com/dec4234/DecsNPCs)
DecsNPCs is a simple solution for NPCs that I made for "The Pit" a while ago. DecsNPCs utilizes packets to spawn and manage NPCs. Functionality is limited however it provided invaluable experience for me in order to better understand packets. We eventually abandoned this project in favor of Citizens2.

## Rust Lang

### [Rustiny](https://github.com/dec4234/Rustiny)
A project nearly identical to the [JavaDestinyAPI](https://github.com/dec4234/JavaDestinyAPI), except in Rust. Uses Serde and Reqwest to make requests to the Bungie.net API and easily parses all of the responses into pre-made structs. Uses tokio to perform async tests, which ensure that functionality for the API remains intact in-between each update. Uses chrono and a custom Zulu Time deserializer to parse time formats.

### [DecCoin](https://github.com/dec4234/DecCoin)
A proof of concept of a Proof-Of-Work CryptoCurrency written in Rust.

### [RND](https://github.com/dec4234/RND)
A packet-based information transfer protocol. Supports serializing and deserializing structs to and from bytes and sending them to connected servers or clients.

### [Endstone](https://github.com/dec4234/Endstone)
An implementation of a Minecraft: Java Edition Server in Rust. Supports the full login sequence up until chunk data is transferred to the client. Supports Server List ping handling.

## C++

### [Data Structures](https://github.com/dec4234/Data_Structures)
Implementations of various data structures in C++, including Linked Lists and Array Lists.
