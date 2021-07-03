# synthwave-x-fluoromachine
This is a fork of @robbowen's [Synthwave '84 theme](https://marketplace.visualstudio.com/items?itemName=RobbOwen.synthwave-vscode), merged with @fullerenedream's [Fluoromachine](https://colorsublime.github.io/themes/FluoroMachine/) theme for VSCode. 

![Theme screenshot](https://repository-images.githubusercontent.com/184457193/69dcff00-14d2-11ea-90e1-4bdf6fef80ca)

## Installation 

• install this theme  
• install [Custom CSS and JS Loader](https://marketplace.visualstudio.com/items?itemName=be5invis.vscode-custom-css)  
• link the CSS file from this extension in your vscode settings.json: 

```
On Mac it might look something like the snippet below:

{
  "vscode_custom_css.imports": [
    "file:///Users/{your username}/.vscode/extensions/webrender.synthwave-x-fluoromachine-0.0.12/synthwave-x-fluoromachine.css",
    "file:///Users/{your username}/.vscode/extensions/webrender.synthwave-x-fluoromachine-0.0.12/epic-80s-transitions.css"
    ]
}

Windows might resemble:

{
  "vscode_custom_css.imports": [
    "file:///C:/Users/{your username}/.vscode/extensions/webrender.synthwave-x-fluoromachine-0.0.12/synthwave-x-fluoromachine.css",
    "file:///C:/Users/{your username}/.vscode/extensions/webrender.synthwave-x-fluoromachine-0.0.12/epic-80s-transitions.css"
    ]
}
```

• epic-80s-transitions.css is optional and brings crazy 80's animations into your VS code!

<p align="center">
  <img src="https://user-images.githubusercontent.com/1646017/124357788-9bbdc680-dc1d-11eb-8d9e-1835933d6bcf.gif" style="box-shadow:0 0 35px #000; width: 80%"/>
</p>

• From the command panel, select `Reload Custom CSS and JS`. You'll need to run this command every time vscode updates.

## Font
The font being used in the screenshot above is [Operator Mono with Ligatures](https://github.com/kiliman/operator-mono-lig).
