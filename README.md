# ssh-tunnel
Forwards port 22 from serveo.net for remote access:  
uses _autossh_, _ssh -R_ option and [serveo.net](https://serveo.net) online service.  
_Usage:_ ssh-tunnel -s/-g [-b]. 
  
**Modes:**  
-s    [s]tandard port 22 SSH tunnel, with alias: rizal72.  
-g    [g]eneric TCP tunnel, use port 1972.  
  
**Available options:**  
-a=ALIAS	set a custom [a]lias.  
-f    execute in background.  
-h    prints this help.  
