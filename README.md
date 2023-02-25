# Supreme Team LaunchingScreens V2.0
  Full credit for the orginal code: https://github.com/dmmarti/

-------
OVERVIEW

(note, web browsers will mess up the syntax of this document, but it will be right when downloaded and reading the README.md file)

This ZIP package is intended to be used with a Raspberry Pi RetroPie/Attract Mode build.

The included shell script is setup for use with RetroPie only.

For users who are using launching/loading screens, this ZIP package contains a script that can be used to download new screen packs as well as change them..

------------
INSTALLATION

Once the ZIP package is downloaded and extracted, copy the launchingscreens.sh shell script to your Pi.

Right now, the script itself is hardcoded to be put into the physical location of:  "/home/pi/RetroPie/retropiemenu"

If you want to put the script into another directory, edit the script file itself and change that line to your own directory location.

Make sure to make the launchingscreens.sh script executable.

chmod 777 launchingscreens.sh

-----
USAGE

The Launching Screens Utility includes a screen pack installer/downloader that operates in much the same way as the Emulation Station Themes manager does.  The script provides a listing of available screen packs for download.  Once selected, the screen pack will be downloaded into the storage folder.

Periodically, new screen packs will be added into the installer script.  Perform an update on the script to retrieve the latest listings.

The script will also allow the easy installation of the screen packs into their respective folders in /opt/retropie/configs.

It will copy the appropriate screen pack's PNG files called:  launching.png

---------------
To Launching Screen pack Authors

Anyone wishing to have their launching screens included needs to follow these guidelines.

1.  upload the screen pack to Github
2.  name the screen pack using this syntax
    launchingscreens-xxxxx     where xxxxx is the screen pack name
    do not include any spaces or special characters
    - and _ are valid
3.  submit a request for inclusion
    a.  make contact via Github
    b.  make contact via Youtube/Facebook/Forums
    c.  submit a Pull Request into the LaunchingThemes repository

