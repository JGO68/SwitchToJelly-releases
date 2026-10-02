# SwitchToJelly

Move from Plex to Jellyfin without losing what you watched.

SwitchToJelly is a Windows app that copies your Plex watch history to Jellyfin: what you
watched, where you stopped, your watchlist and your playlists. For a Plex Home, each member's
history can go to their own Jellyfin user.

## Download

**[Download the latest version](https://github.com/JGO68/SwitchToJelly-releases/releases/latest)**:
on the release page, open **Assets** and run `SwitchToJelly_<version>_x64-setup.exe`.

- Windows 10 or 11, 64-bit.
- Installs for your Windows account only: no administrator rights needed.
- Updates are offered inside the app once installed.

> **Beta:** the installer is not code-signed yet, so Windows SmartScreen may say it
> "protected your PC". Choose **More info**, then **Run anyway**.

## How it works

1. **Connections**: connect to Plex and sign in to your Jellyfin server.
2. **Libraries**: SwitchToJelly matches your Plex libraries with Jellyfin ones, and can
   create the missing ones.
3. **Preview**: see exactly what will change before anything is written.
4. **Migration**: your watch states, progress, watchlist and playlists are written to Jellyfin.
5. **Result**: a report of what was transferred, what was already there, and anything that
   could not be matched with certainty.

Nothing is guessed: an item is updated only when Plex and Jellyfin agree on what it is.

## Licence

Connecting, scanning, matching, the preview and the Jellyfin library setup are free. Writing
your history and lists to Jellyfin needs a licence key. During the beta, testers receive their
key by e-mail.

## Privacy

SwitchToJelly runs on your PC. It talks only to Plex, to your Jellyfin server, and to this
repository to check for updates. Your sign-ins are kept in the Windows Credential Manager. Checking the
licence needs no internet connection.

## Problems or feedback

In the app, open **Diagnostics** and export the file: it contains no password, token, server
address, file path or media title. Then
[open an issue](https://github.com/JGO68/SwitchToJelly-releases/issues) and attach it.

This repository only hosts the installers and the update feed.
