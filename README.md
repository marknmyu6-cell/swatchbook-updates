# SwatchBook

Colours, paint and shape for 3D prints: a Windows app that works alongside Bambu Studio. It matches a project's
colours to the spools in the printer, paints and sculpts models, draws, poses figures, previews slices, and slices
for some resin printers.

This repository holds the releases only.

## Getting it

1. Open **Releases** and download the newest `SwatchBook-<version>.zip`.
2. Unzip it and run **SwatchBook Setup.exe** (Windows 10 or 11). It installs for your Windows user only, with no
   admin rights, and can be taken off again from Settings > Apps.
3. Windows may say it doesn't know the publisher (the Setup isn't signed): choose **More info**, then **Run anyway**.

`Read me first.txt` in the zip has the to-do list for a new PC.

## Updates

SwatchBook that is already installed reads `version.json` here about once a day and offers a newer version by
itself (Help > Check for updates). It downloads the zip from this repository's releases, checks it against the
SHA-256 in `version.json`, and starts its Setup, which asks before installing. Nothing about your PC is sent.

## Licences

The open libraries inside SwatchBook, and their licence texts, are listed in the zip's `Licences` folder.
