# ssh-tunnel
Forwards port 22 from serveo.net for remote access:  
implements _autossh_, _ssh -R_ option and [serveo.net](https://serveo.net) free online service,  
to get a reliable and consistent SSH Tunnel.
_Usage:_ ssh-tunnel -s[-a=ALIAS] / -g / -c[-d=DOMAIN] [-b]. 
  
**Modes:**  
-s    [s]tandard port 22 SSH tunnel, with alias: myAlias.  
-g    [g]eneric TCP tunnel, use port 1972.  
-c    [c]custom domain to forward to. Default: 'ssh.myCustomDomain.com'  
  
**Available options:**   
-b          execute in background.  
-h          prints this help.  

**Optional arguments:**  
-a=ALIAS	set a custom [a]lias.  
-d=DOMAIN   set a custom [d]omain. 