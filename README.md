# Project Annubis - new era of Spyware

### What does it do

Project Annubis was ment to be an admin-free “spyware” that would connect to the attacker, using discord chat communication. The script is written 100% in Python and support few key actions on controlled machine. The program is still in development with the current version 4.1.3 being fourth version since the start of development, and third minor change from the distribution of v4.0. 
The idea was to create free, easy to control spy agent that will work on any platform and work from the end of the world. To start you only need a PC with py installed, Internet and Discord. It’s that easy.

### What do you download?
When you download our spyware you are greeted with two files: `Installer vX.0.bat` & `bot.py`
As you probably imagine `Installer vX.0.bat` is run on the end PC and `bot.py` is your server.

As of now we support
- [ ] Windows

To start you’ll need to edit a `.bat` file to accommodate for your Discord bots. More below in **Tutorial**.

### Available functions
All commands start with _?_ symbol, and to display the commands you’ll need to use `?cmd`
To simplify the usage we decided to divide the commands into two categories:

1. Server side
2. Client side

### Tutorial

1. Download the Annubis package with `Installer vX.0.bat` and `bot.py` inside.
4. Go to discord developer portal - log in and set up two bots 1 Server side & 2 Client side.
5. Create a channel on your server and attach a WEBHOOK onto that server.
6. Edit `install_client.bat` with your own _DISCORD_TOKEN_ & _WEBHOOK_URL_
7. Use `install_client.bat` on the machine you would like to have the spyware running.
8. On attacker (server) side you’ll need to have the `bot.py` up and running to execute commands.

**!MAKE SURE YOU HAVE A PERMISSION TO DO SO!**

### License
Copyright © 2025 GRM Industries
All rights reserved.

This software and all of it's contents may be used for personal or internal
testing purposes only. Modification, redistribution, or public hosting
of this software, in any form, is strictly prohibited without prior
written permission from the author.

The software is provided "AS IS" without warranty of any kind.
Use at your own risk. The author shall not be held liable for any
damages, losses, or issues caused by use of the software.
