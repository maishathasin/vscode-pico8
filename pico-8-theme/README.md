# PICO-8 VSCode Theme

![GitHub issues](https://img.shields.io/github/issues/maishathasin/vscode-pico8)


Welcome to the PICO-8 Theme for Visual Studio Code! This theme is inspired by the aesthetics of the PICO-8 fantasy console's text editor, aiming to bring the nostalgic and retro feel into your modern coding environment.



</br>

Here's a glimpse of how your code will look like with the PICO-8 Theme:

</br>

### Python
![Python](pico-8-theme/images/Python-theme.png)



</br>

### C++
![C++](pico-8-theme/images/cpp-theme.png)

</br>

### Markdown
![Markdown](pico-8-theme/images/Markdown-theme.png)

</br>

### Selection
![Selection](pico-8-theme/images/selection-theme.png)

</br>

## Installation

1. Open the **Extensions** sidebar panel in VS Code. `View → Extensions`

2. Search for `Pico-8 theme`

3. Click `Install`

4. Once installed, you'll be prompted to select Pico-8-theme as your color theme. Confirm the selection.

If you aren't prompted to select a color theme upon installation: `Code (File, on Windows) > Preferences > Color Theme > Pico-8 theme`. Alternatively, you can use the shortcut `⌘/Ctrl + K > ⌘/Ctrl + T` and select `Pico-8 theme`.

<br />

## Typography and cursor 

I am using the pico-8 font from https://fontstruct.com/fontstructions/show/2052852/pico-8-27 , and I  have my own personal settings for the cursor. To change the font and the cursor settings:

1. Download the font and install the font to your computer
    - (MAC USERS): after unzipping the file -> click the **.tff** file and click **Download** 

    ![Download](pico-8-theme/images/download-button-font.png)



2. Open Vscode and then go to the command palette **(Cmd/Ctrl + Shift + P)** and type `"Preferences: Open User Settings (JSON)"`, Edit your user settings to include

```
{
    "[python]": {
        "editor.formatOnType": true
    },
    "solidity.telemetry": false,
    "window.zoomLevel": 1,
    "workbench.colorCustomizations": {
    "editorCursor.foreground": "#FF004D" ,// Pink color for the cursor,
    "editorCursor.background": "#ca597b"  
  },
  "editor.fontSize": 14,
  "editor.cursorWidth": 20,
  "editor.fontWeight": "normal",
  "editor.fontLigatures": true,
  "editor.fontFamily": "PICO-8",
}
``` 


</br>



### Contributions

We welcome any and all feedback, contributions, and suggestions! Feel free to raise an issue on the [Repo's GitHub Issues](https://github.com/maishathasin/vscode-pico8/issues) or submit a Pull Request.

<br/>


**Made with ☕️ and 🌯 by Maisha!**
