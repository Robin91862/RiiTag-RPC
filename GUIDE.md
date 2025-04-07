# RiiTag

**RiiTag** is a customizable and dynamic gamertag. By sharing your gamertag (a dynamic image), you can show what you've been playing to others. A Discord account is required to use RiiTag.

## Requirements

- A computer
- A text editor
- [A Discord account](https://discord.com/login)

## Instructions

### Getting Started

1. Go to the [RiiTag website](https://riitag.t0g3pii.de/).
2. Click the `Login` button on the top right, then sign into your Discord account if you aren't already.
3. Authorize `RiiTag` by clicking `Authorize`.
4. Go to the [RiiTag Account Settings](https://riitag.t0g3pii.de/account/) and copy your key.

> **Note:** To customize your RiiTag, click your profile on the top right of the screen, then select `Edit RiiTag`.

> **Warning:** Do not share your RiiTag key with anyone! If you do, others can abuse your tag.

### Connecting Your USB Loader

#### USB Loader GX

1. Launch USB Loader GX from the list of homebrew.
2. Go to `Settings` > `Features` and enable `Wiinnertag`. Confirm any prompts that appear.
3. Ensure `Initialize Network` is enabled.
4. Close USB Loader GX.
5. Insert the storage device with USB Loader GX into your computer.
6. Go to the RiiTag website, click your profile on the top right, then select `Account`. Download the `Wiinnertag.xml` file.
7. Copy the downloaded `Wiinnertag.xml` to `/apps/usbloader_gx` on the storage device.

> **Success:** You have now set up RiiTag on USB Loader GX. Try launching a game to see if it works.

#### WiiFlow Lite

1. Insert the storage device with WiiFlow Lite into your computer.
2. Open `/apps/wiiflow/wiiflow.ini` in a text editor.
3. Update the following lines:
    - `gamercards_enable=yes`
    - `gamercards=wiinnertag`
    - `wiinnertag_url=https://riitag.t0g3pii.de/wii?game={ID6}&key={KEY}`
    - `wiinnertag_key=<key>` (replace `<key>` with your RiiTag key from the [Getting Started](#getting-started) section).
4. Save the modified `wiiflow.ini`.

> **Success:** You have now set up RiiTag on WiiFlow Lite. Try launching a game to see if it works.

#### Configurable USB Loader

> **Info:** Configurable USB Loader is outdated and may have limited support compared to USB Loader GX and WiiFlow Lite.

> **Tip:** You can use the `CfgLoaderConfigurator.exe` program (Windows only) instead of editing the `config.txt` file.

1. Insert the storage device with Configurable USB Loader into your computer.
2. Open `/usb-loader/config.txt` in a text editor.
3. Update the following lines:
    - `gamercard_url = http://riitag.t0g3pii.de/wii?game={ID6}&key={KEY}`
    - `gamercard_key = <key>` (replace `<key>` with your RiiTag key from the [Getting Started](#getting-started) section).
4. Save the modified `config.txt`.

> **Success:** You have now set up RiiTag on Configurable USB Loader. Try launching a game to see if it works.