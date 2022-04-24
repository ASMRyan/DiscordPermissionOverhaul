# Discord Perms Overhaul

***Channel Access:***
*Any category/channel that is not meant to be viewed by members should be marked as private. This will override the member roles' "View Channels" permission. Below is the list of channels assumed to be privatized for the function of this permissions setup:*

* #staff-stuff
* #gatekeepers
* #bot-wrangling
* #welcome
* #shady-pines
* Voice: The Bunker

## Bot Roles

These roles are for bots only and have specific, high-level permisssions.

* Bots
  * (For security purposes, we should see if we can remove this role and configure individual bots manually. This role has the "Admministrator" permission, which is extremely dangerous to grant to a bot we don't control.)
* Donate Bot
* DBot
* YAGPDB.xyz
* Dyno
* DiscordServers.com
* DISBOARD
* OWO
* GiveawayBot
* Pollmaster
* Piggy
* Piggyusers
* TriviaBot
* RyBot
* Statbot
* Testing testing

## @everyone

* @everyone
  * Guild Perms
    * \+ Embed Links
    * \+ Attach Files
    * \+ Add Reactions
    * \+ Use External Emoji
    * \+ Use External Stickers
    * \+ Read Message History
    * \+ Use Application Commands
    * \+ Connect
    * \+ Use Activities
    * \+ Use Voice Activity
    * \+ Request to Speak
  * Channel Perms
    * #rules
      * \+ View Channel
      * \- Add Reactions
      * \- Use Application Commands
    * #news-and-announcements
      * \- Send Messages
    * #events
      * \- Send Messages
    * #freebies-and-giveaways
      * \- Send Messages
    * #role-room
      * \- Send Messages
    * Voice: Shady Pines
      * \- Use Voice Activity
    * Voice: Surprise Party Planning
      * \- Connect
    * Category: Archived
      * \- Send Messages
      * \- Create Public Threads
    * #main-lobby
      * \- Attach Files
      
## Member Roles

All members should have **only** one of the following:

* Newbie
  * Guild Perms
    * None
  * Channel Perms
    * #welcome
      * \+ View Channel
      * \- Add Reactions
      * \- Use Application Commands

* Member
  * Guild Perms
    * \+ View Channels
    * \+ Create Invite
    * \+ Change Nickname
    * \+ Send Messages
    * \+ Send Messages in Threads
    * \+ Create Public Threads
    * \+ Speak
    * \+ Video
    * \+ Use Voice Activity
    
* Mmbr
  * Guild Perms
    * \+ View Channels
    * \+ Create Invite
    * \+ Change Nickname
    * \+ Send Messages
    * \+ Send Messages in Threads
    * \+ Create Public Threads
    * \+ Speak
    * \+ Video

* Muted
  * Guild Perms
    * \+ View Channels
    * \+ Create Invite
    * \+ Change Nickname

## Staff Roles

All staff should have **only** one of the following roles, *in conjunction* with a member role:

* Gatekeeper
  * Guild Perms
    * None
  * Private Channels
    * #gatekeepers

* Mod
  * Guild Perms
    * \+ Ban Members
    * \+ Manage Messages
  * Private Channels
    * #staff-stuff
    * #gatekeepers
    * Voice: Surprise Party Planning
    
* Op
  * Guild Perms
    * \+ Ban Members
    * \+ Kick Members
    * \+ Manage Messages
  * Private Channels
    * #staff-stuff
    * #gatekeepers
    * Voice: Surprise Party Planning
    
* SrOp
  * Guild Perms
    * \+ Manage Roles
    * \+ Manage Webhooks
    * \+ Ban Members
    * \+ Kick Members
    * \+ Create Private Threads
    * \+ Manage Messages
    * \+ Mention @everyone, @here, and All Roles
  * Private Channels
    * #staff-stuff
    * #gatekeepers
    * #bot-wrangling
    * Voice: Surprise Party Planning
    * Voice: The Bunker
    
* Admin
  * Guild Perms
    * \+ *All Perms Except "Administrator"*
  * Private Channels
    * All Private Channels
    
* Founder
  * Guild Perms
    * \+ Administrator
      * *Gives all permissions and bypasses all restrictions.*
    
### Specialty Staff

For staff who perform duties outside of their typical rank.

* Event Manager
  * Guild Perms
    * \+ Mention @everyone, @here, and All Roles
  * Channel Perms
    * #events
      * \+ Send Messages

* Giveaways
  * Guild Perms
    * None
  * Channel Perms
    * #freebies-and-giveaways
      * \+ Send Messages
    
## Shady Pines

Old fucks.

* Shady Pines Resident
  * Guild Perms
    * None
  * Channel Perms
    * #shady-pines
      * \+ View Channel
    * Voice: Shady Pines
      * \+ Use Voice Activity

## Activist Roles

Traditionally used for write-access in what is now the #politics-activism channel. Possibly relegated to a vanity role at this time.

* Super Activist
* Activist
* Jr. Activist
* A.I.T.

## Vanity Roles

These roles should have no associated permissions.

### Donor Role

Turns user's name pink in the channel.

* Donor

### Nitro Booster Role

Below all functional roles; should not affect user's name color.

* Nitro Booster

### Meetup Roles

Denotes members who have been to the specified meetup.

* Meetup 2021
* Meetup 2019
* Meetup 2018
* Meetup 2017
* Meetup 2016

### Demographic Roles

Self-selected demographic identifiers.

* He/Him
* She/Her
* They/Them
* Ze/Zir/Hir
* Lesbian
* Gay
* Bisexual
* Heterosexual
* Pansexual
* Asexual
* Demisexual
* Aromantic
* Questioning/Unsure (Orientation)
* Transgender
* Nonbinary
* Intersex
* Genderqueer
* Genderfluid
* Queer
* Questioning/Unsure (Gender)
* Africa
* Asia
* Caribbean
* Central America
* Europe
* Oceania
* North America
* South America

### Game Roles

Used to ping groups of interested players for multiplayer games.

* Apex Legends
* Brawlhalla
* Don't Starve Together
* Dungeons & Dragons
* Fortnite
* Grand Theft Auto V
* League of Legends
* Minecraft Minigames
* Overwatch (PC)
* Paladins
* Roblox
* SMITE
* Splitgate
* Starcraft II
* Team Fortress 2
