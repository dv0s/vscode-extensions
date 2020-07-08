# Setting up shell launcher

[Link to answer from stackoverflow](https://stackoverflow.com/questions/43427631/how-to-add-multiple-terminals-in-vs-code)

To setup Shell launcher.  
Go to Files --> Preferences --> Settings and this will open settings.json file and you then insert this (you can edit this to your heart's content):

```
"shellLauncher.shells.windows": [
    {
        "shell": "C:\\Windows\\<sysnative>\\cmd.exe",
        "label": "cmd"
    },
    {
        "shell": "C:\\Windows\\<sysnative>\\WindowsPowerShell\\v1.0\\powershell.exe",
        "label": "PowerShell"
    },
    {
        "shell": "C:\\Program Files\\Git\\bin\\bash.exe",
        "label": "Git bash"
    },
    {
        "shell": "C:\\Windows\\<sysnative>\\bash.exe",
        "label": "WSL Bash"
    }
]
```

PS: You can use shellLauncher.shells.linux for Linux or shellLauncher.shells.osx for macOS.

Go to Files --> Preferences --> Keyboard Shortcuts and then find on {} icon on the top right corner to open keybindings.json file. Insert this

```
[
    { "key": "ctrl+alt+`", "command": "shellLauncher.launch" }
]
```