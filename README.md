# About

This is a tool to generate [Telegram Desktop](https://desktop.telegram.org/) themes from
[pywal](https://github.com/dylanaraps/pywal) or [wal](https://github.com/dylanaraps/wal) files.

Its (mostly) based on [telegram-palette-gen](https://github.com/AryToNeX/telegram-palette-gen.git) script,
but ported to python3 from bash to be less platform-dependent.

# Installation

```bash
git clone https://github.com/s0rg/pywal-tg
cd pywal-tg
python3 pallete-gen.py
```

# Set the color palette

To set the palette follow these steps:

1. Start Telegram Desktop application
2. Go to "Settings / Chat settings"
3. Click three-dots button near the closing cross, the menu will appear, click "Create new theme" option
4. Choose "Import existing theme"
5. Toggle hidden files and select file: ~/.cache/telegram-palette-gen/colors.tdesktop-palette
6. Click on "Keep changes"

# Updating

You can update this tool by running git pull inside your pywal-tg directory:
```bash
cd pywal-tg
git pull
```

# Important notes (from base project)

Some color constants in colors.tdesktop-palette are marked as // [UNTESTED], this because I couldn't find the elements responsable in the app.
So if you find something strange open an issue (with a screenshot of the element and it's name if possible) and I'll fix.

You can also use light colorschemes, no need for extra option, just run the script normally.

The palette works with [wal] too, not just [pywal] and with every color palette that respects the specifications mentioned above.
