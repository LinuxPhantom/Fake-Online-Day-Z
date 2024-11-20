
# Fake Online for DayZ Servers

![Logo](LP.png)

**Fake Online** is a tool designed to simulate increased player activity on your DayZ server by modifying the visible player count on Steam. This mod aims to shed light on the issue of server population inflation and provide a simple solution for server administrators looking to test or experiment with this concept.

![Profile Views](https://komarev.com/ghpvc/?username=LinuxPhantom)

---

## 💀 Disclaimer
- This mod **does not contain malicious code**. If you have concerns, feel free to verify it or delete it after inspection.
- You are solely responsible for any consequences arising from the use of this mod, including potential bans or other actions.
- The mod is intended for educational and testing purposes. Use it responsibly.

---

## 💀 Features
- Increases the player count displayed on Steam, making your server appear more active.
- Fully configurable to display any number of players from **0 to 127**.
- Changes to the fake player count can be made on-the-fly without restarting the server.
- Designed for DayZ version **1.19** (may require updates for future versions).

---

## 💀 Installation Guide
1. Download and extract the mod files.
2. Place the following files in the **root folder** of your DayZ server:
   - `hid.dll`
   - `dzfake.txt`
3. Open `dzfake.txt` and set your desired fake player count (e.g., a value between **0 and 127**).
4. Start your DayZ server.
5. To update the fake player count, simply modify `dzfake.txt`. No server restart is required.

---

## 💀️ Troubleshooting

### Common Issues and Solutions
**Issue**: The server won't start (infinite loop or no response).  
**Solution**: Ensure that the latest version of [Microsoft Visual C++ Redistributable 2015-2022 (x64)](https://aka.ms/vs/17/release/vc_redist.x64.exe) is installed.

**Issue**: The mod stops working after a DayZ update.  
**Solution**: The update may have broken compatibility. Check for mod updates or remove the mod temporarily.

**Issue**: Player count is updated on Steam, but tools like RCon or Wargm don't show the change.  
**Solution**: This is expected behavior. The mod only affects the player count visible on Steam, not other monitoring tools.

---

## 💀 Notes
- This **does not support pirated servers**.
- Fake player counts are only visible to users viewing the server through Steam.
- The does not interact with or modify actual player lists or gameplay.

---

## 💀 Important
The goal of this mod is not to disrupt the DayZ community but to highlight a known issue and offer an opportunity to address it. Use it responsibly and transparently within your server community.

---

## 💀 Contact
For questions, feedback, or to reach me directly:  
[Discord Profile](https://discordapp.com/users/907283934189084682)

---

## 💀 License

```
I Couldn't Care Less Even If You Stuff It Up Your Ass - ICCLEIYSIUYA
====================================================================

Copying and distributing this license is permitted and encouraged. This
license is subject to the terms inside itself so anybody is free to do 
whatever he/she wishes with the license.

Preamble
========

Most computer software license models have been written to prevent the
free distribution and/or modification of software. There are, however,
more liberal license models like GPL but even GPL sets some restrictions,
as most developers know. ICCLEIYSIUYA is a model that removes all rights
and responsibilities of the original writer and sets absolutely no
restrictions as to what the software can be done with.

Terms for copying, distribution and modifications
=================================================

This License is applicable with any Software Product or any Work
(hereafter referred to as "Product") that contains the a written statement
from the Author of the Product implying that the distrubution of the
Product is subject to ICCLEIYSIUYA.

1. Anybody can do anything with the Product. The Product can be copied,
   distributed and modified freely. The Author neither makes claims or has
   any responsibilities regarding the Product. A real-life example: it is
   completely legal to copy a software Product to a USB memory stick and 
   stuff the stick up one's ass or, if preferred, into a living or dead 
   donkey*. The Author may and very probably will lose all interest in the 
   afterlife of the Product and has no responsibility whatsoever as to what
   will happen with the Product after its release. Neither has the Author 
   any obligation to comment the Product, its use, further development or
   anything else, not even when asked politely or impolitely.

*("donkey" is synonym for "ass").
```
