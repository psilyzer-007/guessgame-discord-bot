# guessgame-discord-bot
A Simple two-player Discord Game Bot made using Discord.js. Uses MongoDB for storing user stats.

## What is?
Invite your friends for a guessing challenge. Take turns guessing a random number between a given range (depends on mode). Allows you to play multiple games on different channels. Simple but fun!

## Installation
Install the required dependencies using
```bash
npm install
```
Create the '.env' file in the same folder and add your DISCORDJS_BOT_TOKEN there.

Don't forget to make appropriate changes to the mongoose connection query.

## Commands?
To see all the available commands on Discord
```bash
!gg help
```
To invite a user for a challenge

Available Modes: Easy/Medium/Hard
```bash
!gg invite <mention user> <mode>
```
To accept an invitation use,
```bash
!gg accept <invite code> 
```

Guess a number using,
```bash
!gg guess <number>
```

Check someone's cumulative stats with
```bash
!gg stats <user> 
```



