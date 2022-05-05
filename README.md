# Ubuntu-bugs-journal

#### Wayland and Google Chrome: Maximize with double click on title-bar doesn´t work consistently  
Steps to Reproduce:
1. Start Chromium Browser
2. Double Click on title-bar to maximize window

**Bug Report:** https://bugzilla.redhat.com/show_bug.cgi?id=1947780  
**Quick solution:** Activate "Use System Title and Borders".


### Juniper PRO [Radeon HD 5750]  Graphics Card fan is too loud.
https://help.ubuntu.com/community/RadeonDriver | Already preinstalled on Ubuntu   
https://forums.linuxmint.com/viewtopic.php?t=232889  

key: Juniper PRO [Radeon HD 5750] linux fan loud speed

https://askubuntu.com/questions/174905/opensource-ati-driver-fan-running-at-full-speed-all-the-time

#### Monitor Radeon Graphics Cards
https://linuxhint.com/apps-monitor-amd-gpu-linux/
```
sudo add-apt-repository ppa:radeon-profile/stable
sudo apt update
sudo apt install radeon-profile
```
![image](https://user-images.githubusercontent.com/21064622/166885660-0ba4d23e-0e33-4f8e-9660-1b38bd3de3f2.png)


#### Identify Hardware on Linux
`lspci`
https://www.cyberciti.biz/faq/linux-tell-which-graphics-vga-card-installed/

```
lspci -nn | grep -E 'VGA|Display'
```


#### `Gnome Print Screen Screencast` does not have sound recording.
Gnome Print Screen Video Recording.

#### Install VLC and Change file associations for  .mp4 and .webm
