# web-vnc
just tutorial for accesing(share) vnc through web(HTML5)
<br />

## Installition vnc
```
Download and install any vnc-server 
eg : x11vnc tightvnc
or use package manager like apt & pacman so on 
```
![alt-text](https://raw.githubusercontent.com/aruncs31s/web-vnc/main/Screenshots/Screenshot%20at%202022-03-02%2023-38-02.png)
<br />
## Start a vnc-session 
```
x11vnc (for x11vnc)
vncserver (for tightvnc)
```
[Installing vnc-server  on debian based distros](https://github.com/aruncs31s/web-vnc/tree/main/debian)
[Download tightvnc from here](https://www.tightvnc.com/download.php)
## Install novnc
[Download novnc from here](https://github.com/novnc/noVNC/releases)
<br />
```
cd /usr//share/novnc/utils/
./launch.sh --vnc host:port 
(to get port number use )
ss -tuln | grep  590

```
<img src="https://raw.githubusercontent.com/aruncs31s/web-vnc/main/Screenshots/Screenshot%20at%202022-03-02%2023-20-13.png" width="1600" />
