# 🧙‍♂️Utility to write in NTFS volumes in MAC for free!
## As a service (right click in finder over the volume):
Applescript to make writable NTFS volumes.
Unzip a double click, accept to install the service.
Once is installed right click in **Finder** over a selected volume, then in _services_ or _quick actions_ options the utility should appear.

## [Download the NTFS service](https://github.com/arturogalan/ntfs-mac-automator/raw/master/NTFS%20service.zip "Download the NTFS service")


## As a folder action (automatic detection of Volumes folder)
Applescript to easily make writable NTFS volumes in MAC, just download the zipped file and double click it to install as a ✨**Mac Folder action**✨then when a volume is added it should auto-detect it and prompt the user to make it writable

## [Download the NTFS folder action](https://github.com/arturogalan/ntfs-mac-automator/raw/master/NTFS%20writable%20utility.zip "Download the NTFS folder action")

![NTFS utility](https://github.com/arturogalan/ntfs-mac-automator/blob/master/images/NTFSUtility1.gif)


## Customize the script:

If you want to change the code or the literals, you can [edit the script](https://github.com/arturogalan/ntfs-mac-automator/blob/master/src/NTFS_writable_utility_AppleScript.txt) code and then save it in Automator.
To do this:
* Open the automator program in your mac
* Select a new **Folder action** automation. 
* Add all the code of the script between the on run {input, parameters} and the end run lines, except the utilities functions that goes on the top.
* Then select the folder */Volumes* as the trigger for this action. 
* Make the changes.
* Save it.

## [More info in Medium.](https://medium.com/@arturo.galan/%EF%B8%8Futility-to-write-on-ntfs-volumes-in-mac-for-free-d2d4ab32b25e "Read the explanation of the script")
