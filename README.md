# ssh-tunnel
Forwards port 22 from serveo.net for remote access:  
uses _autossh_, _ssh -R_ option and [serveo.net](https://serveo.net) online service.  
_Usage:_ ssh-tunnel -s/-g/-c [-b]. 
  
**Modes:**  
-s    [s]tandard port 22 SSH tunnel, with alias: rizal72.  
-g    [g]eneric TCP tunnel, use port 1972.  
-c    [c]custom domain to forward to. Default: 'ssh.riccardosallusti.it'  
  
**Available options:**  
-a=ALIAS	set a custom [a]lias.  
-d=DOMAIN   set a custom [d]omain.  
-b          execute in background.  
-h          prints this help.  
