# Discord Bot Joiner Tool

## Introduction
This tool allows users to effortlessly add Discord bots to any server. It streamlines the process, making it easy for developers and server administrators to manage their bots.

## How It Works
1. **Authentication**: The tool uses OAuth2 for authentication, allowing it to securely connect to the Discord API.
2. **Bot Creation**: Upon initialization, the tool checks if the bot is already registered. If not, it will create a new bot instance using the provided token.
3. **Joining a Server**: 
   - The bot requires the `GUILD_MEMBERS` intent to join a server.
   - Once authenticated, the tool sends a request to invite the bot to the specified server using the server ID.
4. **Confirmation**: After sending the invite, the tool listens for a confirmation response from the Discord API, ensuring that the bot has successfully joined the server.
5. **Error Handling**: The tool implements comprehensive error handling to manage any issues that arise during the process, providing feedback on what went wrong.


## How to Install
1.install code

2.extract zip

3.open .exe

4.put the server ID in the "Guild ID: " (Developper mode needed
