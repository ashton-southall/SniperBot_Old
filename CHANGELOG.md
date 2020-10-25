v2.1.4.1 - Project Funding

    + Support URLs now direct through adfoc.us to supply enough income to keep SniperBot running

v2.1.4 - Bug and Confidence Detection fixes

    ~ Fixed bug where detected bot messages would not be deleted
    ~ Re-enabled minimum confidence to delete a message
    ~ Shortened support URLs in messages

v2.1.3 - AI Deletion specific to message type

    + Allow for individual punishment depending on message type in the future

v2.1.1 - Discord Embedded Messages

    ~ All messages from the SniperBot Discord Bot are now sent as embedded messages to make SniperBot look more official

V2.1.0 - Major updates to backend security, enabling possible open source release in the future

    ~ major updates to backend security, enabling the ability to make SniperBot open-source in the future
    ~ migrated to new git Repository, leaving all previous releases including all security issues in old repository allowing SniperBot to be made Open-Source in the      future

V2.0.1 - Discord Blacklist Moderation + AI Logs

    + Admins can make the SniperBotOnTwitch account host a user
    ~ Chat and AI logs save to a logfile for analysis of individual users messages
    + Admins can now modify the Discord Blacklist using chat commands

v2.0.0 - Discord + Twitch - AI Moderation

    + Training Chat AI to read all messages and return if the message should or shouldnt be deleted
    + Twich bot now sends all messages to chat AI to be analysed
    + Discord Bot now sends all messages to chat AI to be analysed
    + Twitch Bot makes moderation actions based off of AI analysis
    + Discord Bot makes moderation actions based off of AI analysis
    + Twitch and Discord bot will only make moderation actions if AI confidence is above 90%
    + Discord bot sends a message in the same channel a message was deleted from containing an explaination, deleted message and sender
    + Discord bot AI ignores messages in NSFW channels

v1.4.0 - Discord - Extreme language detection

    + Discord Bot will now automatically delete messages containing extreme language

v1.3.0 - Twitch - !join and !leave commands

    + Command for anybody to add SniperBot to their channel
    + Command for anybody to Remove SniperBot from their channel

v1.2.3 - Discord - Automatic Blacklist Kick

    + The Discord Bot will now kick blacklisted users from servers when they attempt to chat

v1.2.2 - Twitch - Error catches and automatic timeout

    + SniperBot will now TimeOut blacklisted users instead of banning them, this is so if a user's blacklist status is removed they wont remain banned in channels they have been chatting in
    + Error catching to prevent crashes caused by Bot not having correct permissions

v1.2.1 - Twitch - Chat-Based blacklist management for Administrators

    + Ability for Administrators to manage SniperBot's blacklist via chat commands

v1.2.0 - Twitch - SniperBot chat lurking

    + SniperBot can now lurk in streamers channels to collect information about chatters (for use in a future addition)

v1.1.1 - Twitch - Bot simplification (placing focus on Moderation)

    - Custom Channel Commands

v1.1.0 - Twitch - Blacklisted Users + Shoutout Command

    + SniperBot checks a list of blacklisted users and will timeout any user on that list who tries to chat
    - !coinflip command due to errors
    + !so command to be used by Moderators and the Broadcaster to give a chatter a little shoutout
    + Fixed issue where Broadcasters could not ban chatters

v1.0.4 - Discord - Mass Mention Blocking

    + Custom mass-mention blocking

v1.0.3 - Twitch - Banning

    + Ability for channel moderators and SniperBot administrators to ban users using !ban [username]

v1.0.2 - Twitch - Chat Alerts

    + Basic chat alerts for significant events
    - !refresh command

v1.0.1 - Twitch - Added Developer Commands

    + Added a number of Developer Commands to help with bug testing

v1.0.0 - The Creation Of SniperBot

    + Created SniperBot
