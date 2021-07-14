# Pytron

> This project is very much a Work In Progress

Like Electron for Python backends and without the Chrome runtime. Why?

- 🐍 if you prefer writing (mosty) Python
- 💾 if you want small apps (sub 20mb uncompressed)
- 🖼 if you want to utilise native webviews
- 💪 if you like doing things the hard way :)

Pytron is based on workflows used in [Kanmail](https://kanmail.io). Based on:

- native web windows with [pywebview](https://pywebview.flowrl.com/)
- builds with [pyinstaller](http://www.pyinstaller.org/)
- automatic updates with [pyupdater](https://www.pyupdater.org/)

Pytron brings these together and provides workflows & documentation for:

- combined build & release process 
- code signing (Mac, windows WIP)
- DMG images mac / WiX installers windows (both WIP)
