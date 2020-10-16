## Elegant Code Theme

This is a self customized theme for the Visual Studio Code

> This theme is currently not working and also needs some fixes in order to work fine but you still can use the Vscode Theme by following the steps below.

### Instructions For usage

- Open vscode.
- Open Settings in Json

  - `Ctrl + Shift + p` and search for Preferences: User settings
    Or alternatively you can `Ctrl + ,`
  - Click on the small file icon on the top left corner of your tab area to open it in json

- Copy the contents of `color-customizations.json` and append it to your `settings.json`

> Example

```json
{
  "editor.tokenColorCustomizations": {
    "comments": "#adabab",
    ...
  },
  "workbench.colorCustomizations": {
    "activityBarBadge.background": "#709dc2",
    "activityBar.activeBorder": "#ff1100",
    ...
  }
}

```

**Append or replace if you have existing blocks of `editor.tokenColorCustomizations` and `workbench.colorCustomizations` in your settings.json file.**
