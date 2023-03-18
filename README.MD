# Hogwarts Legacy Save Backup

This script backs up all Hogwarts Legacy saves every 30 minutes while the game is running. Each backup is saved to a *backup-YYYY_MM_DD__HH_MM.zip* file in your backups folder.

Hogwarts Legacy saves all character backups to *%LOCALAPPDATA%\Hogwarts Legacy\Saved\SaveGames* folder. This script simply zips the folder on a timer.

## Installation

* `git clone` or download this repo and save it to a file on your computer.
* Double click `backup.bat`

## Restoring old saves

* Open your LOCALAPPDATA folder by going Start - Run and typing %LOCALAPPDATA%
* Navigate to *Hogwarts Legacy\Saved* folder
* Delete or rename the *SaveGames* folder (CAREFUL! This contains ALL your characters save files)
* Open the backup zip of your choice and extract.
