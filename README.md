# Steam Workshop Downloader

A fully working **Windows desktop application** that allows users who own the **GOG version** of a game to download **Steam Workshop mods** using the ggntw API — no Steam client required.

---

## Features

- Download **single mods** or **bulk downloads** from Steam Workshop URLs.
- Automatic folder organization:
- Toggleable **copy extracted contents** to Processed folder.
- Bulk list with **resizable text box**.
- Change **default download folder** in settings.
- Simple and clean **GUI**.
- Handles download progress, errors, and retries.
- Optional **dark/light themes**.
- Option to **always overwrite files** or skip duplicates.

---

## Installation

1. Create a folder for the application, name it anything you want.
2. Download the exe file and put it in that folder.
3. Create a downloads folder called SteamWorkshop_Downloader or anything you want to store the downloads.
4. Run the application and select your downloads folder when choosing the directory.
5. Now you are all set! I highly recommend enabling Copy Contents to processed since you can just copy everything from the Processed folder in the game id folder to your mods folder really fast.
Also, enable always overwrite because it makes everything simpler, since it sometimes detects faulty duplicates that aren't really there, so overwriting automatically makes the process less of a hassle.

##Troubleshooting
To identify your issue, you need to first check the console below. 
Here are the known issues and how to solve them.

#Error processing https://steamcommunity.com/sharedfiles/filedetails/?id=123456: Resolver failed: {'result': 10, 'status': 3, 'error': 'need login to account'}
If you get this issue, unfortunately, there is no fix for this Steam Workshop item, as it is very recent, meaning the api cannot access it.

#Captcha incomplete Issue
If you get an error saying that the API https://ouo.io/12345 could not be accessed or anything including a link like https://ouo.io/12345, copy and paste it and put it in your browser, as we use the ggntw.com API, and it sometimes thinks you are 
a bot, so if you do this once, and download the file manually or complete the  captcha, it will verify you and allow the downloads from then on for a range of times from 12-36 hours using the software.

