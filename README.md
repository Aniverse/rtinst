# rtinst

This rtinst modification is for my own use. NO SUPPORT. If you have any issues, please use the original rtinst.  

## Installation

```
bash <(curl -Ls https://github.com/Aniverse/rtinst/raw/master/rtsetup)
```
```
bash -c "$(wget --no-check-certificate -qO- https://raw.githubusercontent.com/Aniverse/rtinst/master/rtsetup)"
```
```
rtinst -$options -v $rtorrentVERSION -u $USERNAME -p $PASSWORD -w $WEBPASSWORD 
```
```
rtinst -tfylmi -v 0.9.4 -u aniverse -p kinots74212 -w rutmypa44  
```

- `-t` Do NOT change SSH port  
- `-f` Set FTP port to 21  
- `-y` Force yes to all the questions  
- `-l` Enable logging to ~/rtinst.log  
- `-m` Install the latest master build of rutorrent  
- `-i` Enable IPv6 for rTorrent and libtorrent-rakshasa  
- `-u` Name the user to be primary rtorrent user  
- `-p` Set the unix password  
- `-w` Set the web password for the user  
- `-v` Set the rTorrent version you would like to be installed  





## Modifications

- **New options**  
Using `-i` opinion to enable IPv6 support  
Using `-f` opinion to set FTP port to 21  
Using `-t` opinion to keep the old SSH port  
Using `-v` opinion to select the rtorrent version to be installed  

- **ruTorrent plugins and themes**  
Install club-QuickBox theme  
Install MaterialDesign theme  
Install Filemanager plugin  
Install Fileshare plugin  
Install Mediastream plugin  
Install sox for ruTorrent plugin spectrogram  
Install python cfscrape module for ruTorrent plugin CloudFlare  
Install GeoIP2 plugin instead of GeoIP  
Enable m2ts support for screenshots plugin  
Set min rss interval to 0.1 minutes  

- **Install h5ai as file indexer**  

- **Install ffmpeg 4.2 from static builds**  

- **Install rar, unrar 5.9.0**  

- **Tweak rTorrent default settings**  

- **Do NOT disable root login**  

- **Raised open file limits to 666666**  

- **Setup Nginx Reverse Proxy for some apps**  
This is for [inexistence](https://github.com/Aniverse/inexistence) script.  
Currently it supports Flood, Deluge, qBittorrent, FlexGet, noVNC when using default webui ports.  

- Set SCGIServerTimeout to 60  



## Guides

[The original README](https://github.com/arakasi72/rtinst/blob/master/README.md)  
[The detailed user guide](https://github.com/arakasi72/rtinst/wiki/Guide)  
[The detailed installation guide](https://github.com/arakasi72/rtinst/wiki/Installing-rtinst)  
[License](https://github.com/arakasi72/rtinst/blob/master/LICENSE)  

