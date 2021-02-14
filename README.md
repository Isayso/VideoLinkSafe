# Video Link Safe

New Issue: Update of YT playlists broken - wait for fix of Nuget package

0.6.3 
Youtube channel link can be imported as playlist with hotkey and D&D. (link must have an ID in link like UC....)

0.6.2 
save any internet links with screenshot as thumbnail.  

0.6  
Support for Rumble, Bitchute, Youtube, generic html links.  
D&D of Folders (+crtl subfolders) to lists. Only video files are imported, so you can select all at once.

0.5.7  Hotfix for Youtube changes. The import hotkey now copies the clipboard automatically. No ctrl-c necessary before!
D&D of folders (+Ctrl subfolders) to Linklist and playlist. Imports only playable video formats.  
Known bug: Some videos are not playable in vlc, some are missing the audio track. Unknown cause. 


Save and organize your Video links, local or YouTube in a SQL database. Im-/Export of Kodi playlist files 
Import of NewPipe Database file. Export the database in NewPipe, unzip the file on Windows and import it. 

## Features

### Youtube:  
- Save: links, playlist  
- Play: Browser, vlc, kodi

### Bitchute, Rumble:  
- Save: links  
- Play: Browser  

### Files:    
- Save: Files, folders d&d  
- Play: vlc, Kodi from nfs:NAS  

### html:  
- Save: any link  
- Open: Browser  
  
  
  ![UI](dropzone1.png) 
  
With Kodi video playlist Import/Export function. Hotkey for link import, Youtube playlists import possible.  
Needs youtube-dl to play high resolution videos with vlc.  Drag&Drop support for local video files with thumbnail image generation. 

 ![UI](grid1.png) ![UI](VideoLinkSafe_1.PNG)
   
   
### Install

- Execute .msi file, you will be ask for a SQL Lite file name and location. 

### Quickstart

- add new List
- open it
- drag and drop local video files on list or youtube browser links on import window.

If you copy a YouTube playlist link, you will be asked for a new Listname. This list (blue) will be updated with the "new" button.
 
### Prerequisites

- **Windows with .NET Framework 4.8** 
- VLC player nice to have.
- uses compiled exe of <a href=http://ffmpeg.org>FFmpeg</a> licensed under the <a href=http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html>LGPLv2.1</a> and its source can be downloaded <a href=https://github.com/FFmpeg/FFmpeg>here</a>.


 
## License

This project is licensed under the GPL 3 License - see the [LICENSE](LICENSE) file for details

## Acknowledgments

* Tyrrrz for YoutubeExplode 
* vlc player

Thank you for your great work!
 
 
![GitHub Releases (by Release)](https://img.shields.io/github/downloads/Isayso/VideoLinkSafe/total)

