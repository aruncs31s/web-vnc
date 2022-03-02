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
x11vnc -autoport 5901 (for x11vnc)
vncserver :1 (for tightvnc)
```


[Installing vnc-server  on debian based distros](https://github.com/aruncs31s/web-vnc/tree/main/debian)

<br />

[Download tightvnc from here](https://www.tightvnc.com/download.php)
## Install novnc
[Download novnc from here](https://github.com/novnc/noVNC/releases)
<br />
```

cd /usr//share/novnc/utils/
./launch.sh --vnc host:port 
(to get port number use )
./launch.sh --vnc localhost:5901 (for vnc running on port 1 ie,5901)


```
<br /> 

![alt-text](https://raw.githubusercontent.com/aruncs31s/web-vnc/main/Screenshots/Screenshot%20at%202022-03-02%2023-59-20.png)

<img src="https://raw.githubusercontent.com/aruncs31s/web-vnc/main/Screenshots/Screenshot%20at%202022-03-02%2023-20-13.png" width="1600" />
## accessing 

```
open a web-browser & go to the address given below 
http://127.0.0.1:6080/vnc.html?host=127.0.0.1&port=6080

```
![alt-text](https://raw.githubusercontent.com/aruncs31s/web-vnc/main/Screenshots/Screenshot%20at%202022-03-03%2000-15-19.png)

