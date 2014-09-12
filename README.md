PvPstats
========
# ![logo](https://raw.githubusercontent.com/ShinDarth/PvPstats/master/logo/PvPstats.png)

This software **is still under development and testing phase** but feel free to use it (**keep it updated!**).

[Here](http://www.wowtrilogy.com/pvp/) there is a demo.


## Introduction

PvPstats is an utility for **TrinityCore** and **CMaNGOS** that allows to store and display data about **Battleground scores**. It consists in a core modification and a web application written in **PHP**. It's released under the [GNU GPL v3 License](https://github.com/ShinDarth/PvPstats/blob/master/LICENSE).

Each time a Battleground ends, PvPstats stores in the database all Battlegrounds:

- Date & time
- Winner faction
- Type (which BattleGround is)
- Bracket level range

For each Battleground it also stores player:

- Killing blows
- Deaths
- Honorable Kills
- Bonus Honor
- Score damage done
- and the other various data (like Warsong Gulch capped/returned flags, Arathi Basin assaulted/defended bases, EoS capped flags, etc...)

In a nutshell, **it saves all datas you can see when the BattleGround ends in the score window**.


It currently supports:

- [TrinityCore with Cataclysm (4.x.x game version)](https://github.com/TrinityCore/TrinityCore/tree/4.3.4)
- [TrinityCore with WOTLK (3.x.x game version)](https://github.com/TrinityCore/TrinityCore)
- [CMaNGOS with WOTLK (3.x.x game version)](https://github.com/CMaNGOS/mangos-wotlk)
- [CMaNGOS with TBC     (2.x.x game version)](https://github.com/CMaNGOS/mangos-tbc)
- [CMaNGOS with Classic   (1.x.x game version)](https://github.com/CMaNGOS/mangos-classic)

But since this is a free and open source project, you are more than welcome to fork it and adapt to different emulator or game version.

The web application currently displays the amount of **victories** of **factions**, **top 20 players** and **top 5 guilds** of:

- **Current day**
- **Last 7 days**
- **Current month**
- **Overall**

both **for all levels** and **for every level range (10-19, ... , 70-79, 80)**.

*** **New features for the web application will be implemented soon!** ***

The web applications uses the framework [Bootstrap](https://github.com/twbs/bootstrap) which makes it fully **responsive**, supporting **different window and screen sizes** (e.g. desktop, tablet, mobile, etc..). It also uses the [jQuery](https://github.com/jquery/jquery) JavaScript Library.

## Screenshots

Screenshots will come soon!

## Install

- [How to install PvPstats system in TrinityCore](https://github.com/ShinDarth/PvPstats/blob/master/docs/INSTALL-TrinityCore.md)

- [How to install PvPstats system in CMaNGOS](https://github.com/ShinDarth/PvPstats/blob/master/docs/INSTALL-CMaNGOS.md)
