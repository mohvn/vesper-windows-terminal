![Vesper preview](https://i.imgur.com/eR5yRcL.png)

# Vesper on Windows Terminal

Peppermint and orange flavored dark theme for Windows Terminal.

## Installation
1. Launch Windows Terminal
2. Open the **Settings** panel (<kbd>Ctrl + ,</kbd>)
3. Select **Open JSON file** at bottom left corner (<kbd>Ctrl + Shift + ,</kbd>)
5. Copy the contents of _vesper.json_ into the opened JSON file under **"schemes"**:

```json
{
    "schemes":
    [
        ..vesper theme
        ..other schemes
    ],
}
```
6. Copy the contents of _vesperTheme.json_ into the opened JSON file under **"themes"**:

```json
{
    ..default layout
    "themes":
    [
        ..vesper theme
        ..other themes
    ],
}
```
7. Save and exit
8. In the Settings panel
9. Select **Appearance**
10. Choose *Vesper* in the **Application Theme** drop down menu
11. Click on **Save**.
12. In the **Settings** panel under Profiles, select the profile you want to apply the theme to. **Defaults** will apply to all profiles.
13. Select **Appearance**
14. Choose *Vesper* in the **Color scheme** drop down menu
15. Click on **Save**, enjoy!
---
Based on [Vesper Theme](https://github.com/raunofreiberg/vesper) for VSCode.
