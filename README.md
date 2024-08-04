![Code QL](https://github.com/Project-Plex/TheSportsDB-NFO.bundle/actions/workflows/codeql.yml/badge.svg)

TheSportsDB-NFO.bundle
=================================

# Project Plex - The Sports Database - Plex NFO Importer
## TheSportsDB-NFO.bundle

### Download & Installation

1. Download the [TheSportsDB-NFO.bundle.zip](https://github.com/Project-Plex/Project-Plex.github.io/tree/main/Downloads) from github,
2. extract it,
3. rename it to **TheSportsDB-NFO.bundle**,
4. find the [Plex Media Server data directory](https://support.plex.tv/hc/en-us/articles/202915258-Where-is-the-Plex-Media-Server-data-directory-located)
5. move the .bundle folder to the Plug-ins directory,
6. restart plex and test,
7. if necessary change the owner and permissions of the .bundle and
8. restart plex again.

<img src="https://raw.githubusercontent.com/Project-Plex/Project-Plex.github.io/main/Information/The%20Sports%20Database%20-%20Plex%20NFO%20Importer/_images/winfiles01.jpg" alt="Addon Settings">

<img src="https://raw.githubusercontent.com/Project-Plex/Project-Plex.github.io/main/Information/The%20Sports%20Database%20-%20Plex%20NFO%20Importer/_images/winfiles02.jpg" alt="Addon Settings">

### Download & Installation on ubuntu

1. Download from github and unzip
2. Remove "-master" from the end of both folder names.
3. Copy them to the folder:  /var/lib/plexmediaserver/Library/Application Support/Plex Media Server/Plug-ins
4. Find the group number for user "plex" by command "id plex".
5. "cd" to folder in step 3 and change ownership of both folder bundles: "sudo chown plex:{gid} XBMC*"
6. run "sudo service plexmediaserver restart".


## Documentation:

Please use the: <a href="https://github.com/Project-Plex/Project-Plex.github.io/tree/main/Information/The%20Sports%20Database%20-%20Plex%20NFO%20Importer" target="_blank">Plex NFO Importer Documentation</a>

## Support:

Project Plex: <a href="https://github.com/Project-Plex/">https://github.com/Project-Plex/</a> | Project Kodi: <a href="https://github.com/Project-Kodi/">https://github.com/Project-Kodi/</a>

<a href="https://discord.com/channels/481047912286257152/481047912286257155"><img src="https://raw.githubusercontent.com/Project-Plex/PlexSportScanner/master/Information/images/discord-logo.png" alt="Join the chat at Discord" height="24"></a> Join us at Discord: <a href="https://discord.com/channels/481047912286257152/481047912286257155">TheDataDB</a>

## Information about this Project:

 NFO file Importer Agent for Plex, that uses www.thesportsdb.com