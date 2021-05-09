# mpv-copyTime
Copy the current time of the video to clipboard.

Get the current time of the video and copy it to the clipboard with the format HH:MM:SS.MS, where MS (milliseconds) is 3 digits.

By default, the script is bound to "Ctrl + c"

# Installation

## Windows
For Windows use `copyTime.js` or `copyTime.lua`, the one you prefer.

* Put the selected script in your scripts folder (usually `"%APPDATA%\mpv\scripts"`).

The script needs PowerShell to work.

## GNU/Linux

For GNU/Linux use `copyTime.lua`, which supports Windows and GNU/Linux.
Powershell is used on Windows and `xclip` is used on GNU/Linux.

* Put `copyTime.lua` in your scripts folder (usually `"~/.config/mpv/scripts/"`).

# Screenshot
![ss1](https://user-images.githubusercontent.com/40000640/111867156-02f68a00-8951-11eb-84a8-c78616c68aa3.PNG)
