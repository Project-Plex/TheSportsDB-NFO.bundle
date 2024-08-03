![Code QL](https://github.com/Project-Plex/TheSportsDB-NFO.bundle/actions/workflows/codeql.yml/badge.svg)

### Plex NFO Importer for TheSportsDB - Project Plex

TheSportsDB-NFO.bundle
=================================
## Installation:

1. Download the [TheSportsDB-NFO.bundle.zip](https://github.com/Project-Plex/Project-Plex.github.io/tree/main/Downloads) from github,
2. extract it,
3. rename it to **TheSportsDB-NFO.bundle**,
4. find the [Plex Media Server data directory](https://support.plex.tv/hc/en-us/articles/202915258-Where-is-the-Plex-Media-Server-data-directory-located)
5. move the .bundle folder to the Plug-ins directory,
6. restart plex and test,
7. if necessary change the owner and permissions of the .bundle and
8. restart plex again.

Install on ubuntu as example:
- Download from github and unzip
- Remove "-master" from the end of both folder names.
- Copy them to the folder:  /var/lib/plexmediaserver/Library/Application Support/Plex Media Server/Plug-ins
- Find the group number for user "plex" by command "id plex".
- "cd" to folder in step 3 and change ownership of both XBMC bundles: "sudo chown plex:{gid} XBMC*"
- run "sudo service plexmediaserver restart".
Done.

## Documentation:

Please use our documentation first: <a href="https://github.com/Project-Plex/Project-Plex.github.io">https://github.com/Project-Plex/Project-Plex.github.io</a>

## Support:

Project Plex: <a href="https://github.com/Project-Plex/">https://github.com/Project-Plex/</a> | Project Kodi: <a href="https://github.com/Project-Kodi/">https://github.com/Project-Kodi/</a>

<a href="https://discord.com/channels/481047912286257152/481047912286257155"><img src="https://raw.githubusercontent.com/Project-Plex/PlexSportScanner/master/Information/images/discord-logo.png" alt="Join the chat at Discord" height="24"></a> Join us at Discord: <a href="https://discord.com/channels/481047912286257152/481047912286257155">TheDataDB</a>

## Information about this Project:

 NFO file Importer Agent for Plex, that uses www.thesportsdb.com
