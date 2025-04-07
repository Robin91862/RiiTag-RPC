# Riitag

**RiiTag** is a customizable and dynamic gamertag. By sharing your gamertag (a dynamic image), you can show what you've been playing to other people. You need a Discord account to use RiiTag.

## Requirements
-   A computer
-   A text editor
-   [A Discord account](https://discord.com/login)

### Instructions
#### Getting started

1.  [Go to the t0g3pii's RiiTag website](https://riitag.t0g3pii.de/)
2.  Press the Login button on the top right, then sign into your Discord account if you aren't already
3.  A dialog will appear asking if you want to authorize `Riitag`, press Authorize

-   If you'd like to customize your RiiTag, press on your profile that is on the top right of the screen, then Edit RiiTag

![Warning icon](https://upload.wikimedia.org/wikipedia/commons/thumb/f/f1/OOjs_UI_icon_information-warning.svg/20px-OOjs_UI_icon_information-warning.svg.png) <u>*Do not share your RiiTag key with anyone! If you do, people can abuse your tag.*</u>

## Connecting your USB Loader

### USB Loader GX

1.  Launch USB Loader GX from the list of homebrew
2.  Go to `Settings`, then `Features` and turn `Wiinnertag` on. Press Yes or OK to any prompts that appear.
3.  Ensure that `Initialize Network` is enabled
4.  Close USB Loader GX
5.  Insert the storage device that has USB Loader GX into your computer
6.  Go to the website again, then press on your profile that is on the top right of the screen, then Account, then press You can also download your Wiinnertag.xml. which will download the file needed for RiiTag usage
7.  Copy the downloaded `Wiinnertag.xml` to `/apps/usbloader_gx` on the storage device that has USB Loader GX.

![Success icon](https://upload.wikimedia.org/wikipedia/commons/thumb/1/17/OOjs_UI_icon_information-constructive.svg/20px-OOjs_UI_icon_information-constructive.svg.png) <u>*You have now set up RiiTag on USB Loader GX. Try launching a game to see if it works*</u>


### WiiFlow

1.  Insert the storage device that has WiiFlow into your computer
2.  Open `/apps/wiiflow/wiiflow.ini` in a text editor
3.  Search for `gamercards` then replace it with `gamercards=wiinnertag`
4.  Search for `wiinnertag_url` and replace it with `wiinnertag_url=https://riitag.t0g3pii.de/wii?game={ID6}&key={KEY}`
5.  Search for `wiinnertag_key` and replace that line with `wiinnertag_key=<key>`, replacing <key> with the key you wrote down in [Section I](https://wiki.hacks.guide/wiki/RiiTag#Getting_started "RiiTag")
6.  Search for `gamercards_enable` and replace it with `gamercards_enable=yes`.
7.  Save the modified `wiiflow.ini`

![Success icon](https://upload.wikimedia.org/wikipedia/commons/thumb/1/17/OOjs_UI_icon_information-constructive.svg/20px-OOjs_UI_icon_information-constructive.svg.png) <u>*You have now set up RiiTag on WiiFlow. Try launching a game to see if it works*</u>


### Configurable USB Loader

![Info icon](https://upload.wikimedia.org/wikipedia/commons/thumb/e/ec/OOjs_UI_icon_information-progressive.svg/20px-OOjs_UI_icon_information-progressive.svg.png) <u>*Configurable USB Loader is a heavily outdated USB loader and you have less chance of getting support for it compared to USB Loader GX and WiiFlow Lite.*</u>

![Info icon](https://upload.wikimedia.org/wikipedia/commons/thumb/e/ec/OOjs_UI_icon_information-progressive.svg/20px-OOjs_UI_icon_information-progressive.svg.png) <u>*You can use the `CfgLoaderConfigurator.exe` program (Windows only) instead of editing the `config.txt` file mentioned below if you want to.*</u>

1.  Insert the storage device that has Configurable USB Loader into your computer
2.  Open `/usb-loader/config.txt` in a text editor
3.  Replace (or add) the line starting with `gamercard_url` with `gamercard_url = http://riitag.t0g3pii.de/wii?game={ID6}&key={KEY}`
4.  Replace (or add) the line starting with `gamercard_key` with `gamercard_key = <key>`, replacing <key> with the key you wrote down in [Section I](https://wiki.hacks.guide/wiki/RiiTag#Getting_started "RiiTag")
5.  Save the modified `config.txt`

![Success icon](https://upload.wikimedia.org/wikipedia/commons/thumb/1/17/OOjs_UI_icon_information-constructive.svg/20px-OOjs_UI_icon_information-constructive.svg.png) <u>*You have now set up RiiTag on Configurable USB Loader. Try launching a game to see if it works*</u>


## RiiTag-RPC

### Requirements

-   [RiiTag RPC](https://github.com/t0g3pii/RiiTag-RPC/releases/latest)

#### Instructions

![Info icon](https://upload.wikimedia.org/wikipedia/commons/thumb/e/ec/OOjs_UI_icon_information-progressive.svg/20px-OOjs_UI_icon_information-progressive.svg.png) <u>*This program shows your current game on your Discord profile, alongside your RiiTag*</u>

1.  Run the downloaded executable for your system
2.  Once it has loaded, press enter to show the login prompt
3.  A dialog will appear asking if you want to authorize `Riitag`, press Authorize

![Success icon](https://upload.wikimedia.org/wikipedia/commons/thumb/1/17/OOjs_UI_icon_information-constructive.svg/20px-OOjs_UI_icon_information-constructive.svg.png) <u>*You will now be logged into RiiTag RPC. Try launching a game to see if it works*</u>

## UTag

![Info icon](https://upload.wikimedia.org/wikipedia/commons/thumb/e/ec/OOjs_UI_icon_information-progressive.svg/20px-OOjs_UI_icon_information-progressive.svg.png) <u>*This requires you have a [Modded Wii U](https://wiiu.hacks.guide/ "wiiuguide:") running the [Aroma environment](https://wiiu.hacks.guide/aroma/getting-started "wiiuguide:aroma/getting-started")*</u>

### Requirements

-   [UTag](https://github.com/t0g3pii/UTag/releases/latest)
-   [Notepad++](https://notepad-plus-plus.org/downloads/)

#### Instructions

1.  Insert your SD card into your computer
2.  Open `UTag-v2.2.0.zip` and copy utag.wps to `wiiu/environments/aroma/plugins/`
3.  [Go to the t0g3pii's RiiTag website](https://riitag.t0g3pii.de/)
4.  Press the Login button on the top right, then sign into your Discord account if you aren't already
5.  A dialog will appear asking if you want to authorize `RiiConnect24 Login`, press Authorize
6.  Press on your profile that is on the top right of the screen, then Account, then press Copy which will copy your RiiTag key

![Warning icon](https://upload.wikimedia.org/wikipedia/commons/thumb/f/f1/OOjs_UI_icon_information-warning.svg/20px-OOjs_UI_icon_information-warning.svg.png) <u>*Do not share your RiiTag key with anyone! If you do, people can abuse your tag.*</u>

8.  Create a Text Document called `utag.txt` in the `wiiu` folder that is on the root of your SD card
9.  Open Notepad++, then go to File > Open, then go to the `utag.txt` file you just created
10.  Paste your RiiTag key inside the text document, then go to File > Save

![Success icon](https://upload.wikimedia.org/wikipedia/commons/thumb/1/17/OOjs_UI_icon_information-constructive.svg/20px-OOjs_UI_icon_information-constructive.svg.png) <u>*You have now set up RiiTag on your Wii U. Try launching a game to see if it works*</u>

