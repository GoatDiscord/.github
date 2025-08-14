# To-Do List

This file tracks the status of the Goat Bot project, including completed features and ideas for future implementations.

## Implemented Features

### Core & Management

* [x] **Web Dashboard**: Intuitive web interface to manage the bot’s configuration.
* [x] **Discord Authentication**: Secure login via Discord OAuth2.
* [x] **Server Selector**: Page for administrators to choose which server to configure.
* [x] **Dynamic Command System**: Base and custom commands are deployed and updated automatically.
* [x] **Bot Profile Customization**: Ability to change the bot’s nickname and presence from the dashboard.
* [x] **Server Statistics**: Main panel with activity analytics and command usage.
* [x] **Event Logs**: Granular configuration to record server events (joins, leaves, edits, etc.).

### Moderation & Security

* [x] **Manual Moderation**: Commands for `ban`, `kick`, `mute`, `unmute`, `warn`, `purge`.
* [x] **Moderation History**: Commands like `history` and `warnings` to review a user’s history.
* [x] **AI Auto-Moderation**: Automatic detection and removal of toxic, spam, or inappropriate messages.
* [x] **Discord AutoMod Integration**: Manage Discord’s native AutoMod rules from the dashboard.
* [x] **Reports System**: `/report` command and context menu for users to report messages or members.
* [x] **Ban Appeal System**: Public webpage for appeals and a management panel for moderators.
* [x] **Verification Gate**: System requiring new members to verify their identity before accessing the server.
* [x] **Anti-Raid**: Protection against mass user joins.
* [x] **Support Ticket System**: A professional tool for members to request private help from the moderation team in an organized and confidential way.

### Interaction & Community

* [x] **AI Welcome & Farewell Messages**: Customizable messages in text, embed, or image format.
* [x] **Reaction Roles**: Automatic role assignment through message reactions.
* [x] **Leveling & XP System**: Users earn XP through activity, with `/rank` and `/leaderboard` commands.
* [x] **Giveaway System**: `/giveaway` command to automatically create and manage giveaways.
* [x] **Poll System**: `/poll` command to create polls with button voting.
* [x] **Info Commands**: `/userinfo`, `/serverinfo`, and `/profile` with visual cards.
* [x] **Starboard**: A “best-of” channel for the server, curated by the community.

### Automation & Utility

* [x] **Custom Commands**: Create simple text-response commands from the dashboard.
* [x] **AI Command Generator**: Tool to generate code for new commands from a prompt.
* [x] **Embed Builder**: Visual interface to design and save complex embed messages.
* [x] **Scheduled Announcements**: Schedule text or embed messages to be sent in the future.
* [x] **Auto-Roles**: Automatically assign roles to new members upon joining.

---

## Future Features

* [ ] **Economy & Role Shop**

  * **Description**: A virtual economy system where users earn “coins” through activity, which they can spend in a shop to buy cosmetic roles.
  * **Components**: `/balance`, `/shop`, `/buy`, `/daily` commands; configuration panel.
  * **Benefit**: Gamifies participation and rewards the most dedicated members.

* [ ] **Music Module**

  * **Description**: Allows users to play music from sources like YouTube or Spotify in voice channels.
  * **Components**: `/play`, `/skip`, `/queue`, `/stop` commands; song queue system; volume control.
  * **Benefit**: Boosts social interaction and makes voice channels more engaging.

* [ ] **Backups Module**

  * **Description**: A system to create and restore backups of server configurations, such as roles, channels, and permissions.
  * **Components**: “Create Backup” button in the dashboard; list of backups with restore option.
  * **Benefit**: Provides a safety net against errors or malicious actions.

* [ ] **Social Media Webhooks Integration**

  * **Description**: Automatically posts new content from platforms like Twitter, YouTube, or Twitch into designated channels.
  * **Components**: Configuration panel to add profile URLs and select target channels.
  * **Benefit**: Keeps the server automatically updated with relevant content.

* [ ] **Games & Activities**

  * **Description**: Commands to launch interactive mini-games directly in text channels.
  * **Components**: Commands for games like `/trivia`, `/akinator`, or `/connect-four`.
  * **Benefit**: Encourages fun interaction and casual community participation.

* [ ] **Enhanced Reaction Roles with Panel Builder**

  * **Description**: Upgrade the reaction role system to allow admins to create and manage role “panels” directly from a visual interface in the dashboard.
  * **Components**: Dashboard interface to create a message (title, description) and link multiple emoji/role pairs.
  * **Benefit**: Significantly improves the user experience, makes the feature more powerful, and centralizes configuration in the dashboard.

* [ ] **Birthdays Module**

  * **Description**: Allows users to register their birthday so the bot can automatically announce and celebrate it in the server.
  * **Components**: `/birthday set <date>`, `/birthday remove` commands; temporary “Birthday” role; customizable announcement.
  * **Benefit**: Creates a more personal and friendly community atmosphere.

* [ ] **Suggestions Module**

  * **Description**: A structured system for members to submit suggestions for the server, which can then be voted on by the community.
  * **Components**: `/suggest <idea>` command; the bot posts the suggestion in a designated channel with voting buttons; admin commands for `/approve` or `/deny`.
  * **Benefit**: Organizes and democratizes community feedback.

* [ ] **Stream Notifications**

  * **Description**: Automatically announces in a channel when a member (with a specific role) goes live on Twitch.
  * **Components**: Configuration panel to link a Twitch account and select a role and notification channel.
  * **Benefit**: Supports content creators within the community and keeps members informed.

* [ ] **Temporary Voice Channels**

  * **Description**: Creates “join-to-create” voice channels that generate a temporary channel for the user, which is deleted once empty.
  * **Components**: Dashboard setting to designate a “lobby” channel; temporary management permissions for the channel creator.
  * **Benefit**: Keeps the voice channel list clean and organized, providing private spaces on demand.

* [ ] **AI-Powered Polls**

  * **Description**: Enhances the current poll command by allowing AI to generate poll questions and options based on a topic.
  * **Components**: `/poll ai <topic>` command that generates a relevant poll to keep the community engaged.
  * **Benefit**: Saves moderators time and sparks interesting discussions with minimal effort.

---

